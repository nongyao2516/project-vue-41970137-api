<template >
    <div class="container my-5">
    <div class="d-flex justify-content-center align-items-center vh-100">
    <div class="card shadow p-4" style="width: 400px; border-radius: 15px;">
      <h3 class="text-center mb-4">Register</h3>
      <form>
        <div class="mb-3">
          <label  class="form-label">ชื่อ</label>
          <input type="text" class="form-control" id="fname" placeholder="ชื่อ" required>
        </div>
        <div class="mb-3">
          <label  class="form-label">นามสกุล</label>
          <input type="text" class="form-control" id="lname" placeholder="นามสกุล" required>
        </div>
        <div class="mb-3">
          <label  class="form-label">เบอร์โทรศัพท์</label>
          <input type="text" class="form-control" id="phone" placeholder="เบอร์โทรศัพท์" required>
        </div>
        <div class="mb-3">
          <label  class="form-label">Username</label>
          <input type="text" class="form-control" id="username" placeholder="username" required>
        </div>
        <div class="mb-3">
          <label  class="form-label">Password</label>
          <input type="password" class="form-control" id="phone" placeholder="password" required>
        </div>

        <button type="submit" class="btn btn-primary w-100">บันทึก</button>
        
      </form>
    </div>
  </div>
    </div>
</template>
