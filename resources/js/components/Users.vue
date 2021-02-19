<template>
    <div class="container">
     <div class="row mt-5">
          <div class="col-12">
            <div class="card">
              <div class="card-header">
                <h3 class="card-title">Users Table</h3>

                <div class="card-tools">  
                     <b-button v-b-modal.modal-1 class="btn btn-success">
                       Add New <i class="fas fa-user-plus fa-fw"></i>
                       </b-button>
                        
                </div>
              </div>
              <!-- /.card-header -->
              <div class="card-body table-responsive p-0">
                <table class="table table-hover">
                  <thead>
                    <tr>
                      <th>ID</th>
                      <th>User</th>
                      <th>Email</th>
                      <th>Type</th>
                      <th>Modify</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>183</td>
                      <td>John Doe</td>
                      <td>11-7-2014</td>
                      <td><span class="tag tag-success">Approved</span></td>
                      <td>
                           <a href="#"><i class="fa fa-edit blue fa-fw"></i></a> | 
                           <a href="#" ><i class="fa fa-trash red fa-fw"></i></a>
                     </td>
                    </tr>
                  </tbody>
                </table>
              </div>
              <!-- /.card-body -->
            </div>
            <!-- /.card -->
          </div>
        </div>

       <div>
            <b-modal id="modal-1" title="Add New User">
            <form>
                  <div class="form-group row">
                          <label for="inputEmail3" class="col-sm-2 col-form-label">Email</label>
                          <div class="col-sm-10">
                          <input type="email" class="form-control" id="inputEmail3">
                          </div>
                          </div>
                          <div class="form-group row">
                          <label for="inputPassword3" class="col-sm-2 col-form-label">Password</label>
                          <div class="col-sm-10">
                          <input type="password" class="form-control" id="inputPassword3">
                          </div>
                          </div>
            </form>
            </b-modal>

       </div>

    </div>
</template>

<script>
 
</script>
