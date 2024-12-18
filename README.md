<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css"> 
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

<form>
  <div class="form-group row">
    <label for="nama" class="col-4 col-form-label">Nama Lengkap</label> 
    <div class="col-8">
      <input id="nama" name="nama" type="text" required="required" class="form-control">
    </div>
  </div>
  <div class="form-group row">
    <label for="tempat lahir" class="col-4 col-form-label">Tempat Lahir</label> 
    <div class="col-8">
      <input id="tempat lahir" name="tempat lahir" type="text" required="required" class="form-control">
    </div>
  </div>
  <div class="form-group row">
    <label for="tanggal" class="col-4 col-form-label">Tanggal Lahir</label> 
    <div class="col-8">
      <div class="input-group">
        <input id="tanggal" name="tanggal" type="text" required="required" class="form-control"> 
        <div class="input-group-append">
          <div class="input-group-text">
            <i class="fa fa-calendar"></i>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label class="col-4">Gender</label> 
    <div class="col-8">
      <div class="custom-control custom-radio custom-control-inline">
        <input name="perempuan" id="perempuan_0" type="radio" required="required" class="custom-control-input" value="pria"> 
        <label for="perempuan_0" class="custom-control-label">Laki-Laki</label>
      </div>
      <div class="custom-control custom-radio custom-control-inline">
        <input name="perempuan" id="perempuan_1" type="radio" required="required" class="custom-control-input" value="wanita"> 
        <label for="perempuan_1" class="custom-control-label">Perempuan</label>
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="email" class="col-4 col-form-label">Email</label> 
    <div class="col-8">
      <div class="input-group">
        <div class="input-group-prepend">
          <div class="input-group-text">
            <i class="fa fa-at"></i>
          </div>
        </div> 
        <input id="email" name="email" type="text" class="form-control" required="required">
      </div>
    </div>
  </div>
  <div class="form-group row">
    <label for="select" class="col-4 col-form-label">Status Peserta</label> 
    <div class="col-8">
      <select id="select" name="select" class="custom-select" required="required">
        <option value="siswa">Siswa</option>
        <option value="mahasiswa">Mahasiswa</option>
        <option value="pekerja">Pekerja</option>
      </select>
    </div>
  </div> 
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button name="submit" type="submit" class="btn btn-primary">Daftar</button>
    </div>
  </div>
</form>
