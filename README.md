<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Form Registrasi</title>
    <link
          href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
          rel="stylesheet"
        />
      </head>
      <body>
        <div class="container mt-5">
          <div class="row">
            <!-- Form Framework Bootsrap -->
            <div class="col-md-6">
              <div class="card">
                <div class="card-header text-center">
                  <h3>Register</h3>
                </div>
                <div class="card-body">
                  <form action="#" method="post" enctype="multipart/form-data">
                    <div class="mb-3">
                      <label for="nama1" class="form-label">Nama Depan:</label>
                      <input type="text" class="form-control" id="nama1" name="nama1" placeholder="isi disini" required/>
                    </div>

                    <div class="mb-3">
                      <label for="nama2" class="form-label">Nama Belakang:</label>
                      <input type="text" class="form-control" id="nama2" name="nama2" placeholder="isi disini" required/>
                    </div>

                    <div class="mb-3">
                      <label for="alamat" class="form-label">Alamat:</label>
                      <input type="text" class="form-control" id="alamat" name="alamat" placeholder="isi disini" required/>
                    </div>

                    <div class="mb-3">
                        <label for="tl" class="form-label">Tanggal Lahir:</label>
                        <input type="text" class="form-control" id="tl" name="tl" placeholder="isi disini" required/>
                      </div>
  
                      <div class="mb-3">
                        <label for="jk" class="form-label">Jenis Kelamin:</label>
                        <input type="text" class="form-control" id="jk" name="jk" placeholder="isi disini" required/>
                      </div>
  
                      <div class="mb-3">
                        <label for="email" class="form-label">Email:</label>
                        <input type="text" class="form-control" id="email" name="email" placeholder="isi disini" required/>
                      </div>

                      <div class="mb-3">
                        <label for="user" class="form-label">Username:</label>
                        <input type="text" class="form-control" id="user" name="user" placeholder="isi disini" required/>
                      </div>
  
                      <div class="mb-3">
                        <label for="pass" class="form-label">Password:</label>
                        <input type="text" class="form-control" id="pass" name="pass" placeholder="isi disini" required/>
                      </div>
  
                      <div class="mb-3">
                        <label for="Koment" class="form-label">Komentar:</label>
                        <input type="text" class="form-control" id="koment" name="koment" placeholder="isi disini" required/>
                      </div>

                    <div class="mb-3">
                      <label for="file" class="form-label">Upload:</label>
                      <input type="file" class="form-control" id="file" name="file" />
                    </div>
      
                      <div class="d-grid">
                        <input type="submit" class="btn btn-primary" value="kirim" />
                      </div>
                    </form>
                  </div>
                </div>
              </div>

    <!-- Form Pure HTML -->
    <style>
      body {
        font-family: Arial, sans-serif;
      }
      .form-container {
        width: 300px;
        margin: 0 auto;
        padding: 10px;
        border: 1px solid #000;
      }
      .form-container input[type="text"],
      .form-container input[type="email"],
      .form-container textarea {
        width: 100%;
        padding: 5px;
        margin: 5px 0;
        box-sizing: border-box;
      }
      .form-container input[type="file"] {
        margin: 5px 0;
      }
      .form-container label {
        display: block;
        margin-top: 8px;
      }
      .form-container input[type="submit"] {
        margin-top: 10px;
        padding: 5px 10px;
        background-color: #001aff;
        color: white;
        border: none;
        cursor: pointer;
      }
    </style>
  </head>
  <body>
    <div class="form-container">
      <form action="#" method="post" enctype="multipart/form-data">
        <h3>Register</h3>
        <label for="nama1">Nama Depan:</label>
        <input type="text" id="nama1" name="nama1" placeholder="isi disini" required/>

        <label for="nama2">Nama Belakang:</label>
        <input type="text" id="nama2" name="nama2" placeholder="isi disini" required/>

        <label for="alamat">Alamat:</label>
        <input type="text" id="alamat" name="alamat" placeholder="isi disini" required/>

        <label for="tl">Tanggal Lahir:</label>
        <input type="text" id="tl" name="tl" placeholder="isi disini" required/>

        <label for="jk">Jenis Kelamin:</label>
        <input type="text" id="jk" name="jk" placeholder="isi disini" required/>

        <label for="email">Email:</label>
        <input type="text" id="email" name="email" placeholder="isi disini" required/>

        <label for="username">Username:</label>
        <input type="text" id="username" name="username" placeholder="isi disini" required/>

        <label for="pass">Password:</label>
        <input type="text" id="pass" name="pass" placeholder="isi disini" required/>

        <label for="koment">Komentar:</label>
        <textarea type="text" id="Koment" name="Koment" rows="5" placeholder="isi disini" required ></textarea>

        <label for="file">Upload :</label>
        <input type="file" id="file" name="file" />

        <input type="submit" value="kirim" />
      </form>
    </div>
  </body>
</html>
