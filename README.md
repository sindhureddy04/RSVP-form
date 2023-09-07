# RSVP-form
using Bootstrap to create a RSVP form

index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width,intial-scaled=1">
    <title>Form with Bootstrap</title>
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/js/bootstrap.bundle.min.js" integrity="sha384-qKXV1j0HvMUeCBQ+QVp7JcfGl760yU08IQ+GpUo5hlbpg51QRiuqHAJz8+BrxE/N" crossorigin="anonymous"></script>
  </head>
  <body class="bg-info">
     <body class="bg-info">
    <style>
      .container-sm{
        max-width: 700px;
      }
    </style>
    <div class="container-sm">
      <main>
        <div class="py-5 text-center">
          <h1>RSVP form</h1>
          <p clas="lead">using Bootstrap to create a RSVP form</p>
        </div>
        <div>
          <div class="my-4">
          <form class="needs-validation" novalidate>
            <div class="row g-3">
              <div class="col-sm-6">
                <label for="firstName" class="form-label">Frist name</label>
                <input type="text" class="form-control" id="firstName" placeholder="" value="" required>
                <div class="invalid-feedback"> Valid first name is required.</div>
                <div class="col-sm-6">
                <label for="lastName" class="form-label">Last name</label>
                <input type="text" class="form-control" id="lastName" placeholder="" value="" required>
                <div class="invalid-feedback"> Valid last name is required.</div>
                <div class="col-sm-6">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" placeholder="" value="" required>
                <div class="invalid-feedback"> Please enter a vaild email address.</div>
                  <div class="col-sm-6">
                <label for="phone" class="form-label">Phone Number</label>
                <input type="tel" class="form-control" id="phone" patttern="[0-9] {10,12}" required>
                <div class="invalid-feedback"> Please enter a vaild phone number.</div>
              <div class="col-sm-5">
                <label for="country" class="form-label">country</label>
               <select class="form-select" id="country" required>
                <option value="">choose....</option>
                 <option> India</option>
                <div class="invalid-feedback"></div>
              <div class="col-sm-5">
                <label for="State" class="form-label">country</label>
               <select class="form-select" id="state" required>
                <option value="">choose....</option>
                 <option> AndhraPradhesh</option>
                <div class="invalid-feedback"></div>  
        </div>
      </main>
</html>

style.css
html {
  height: 100%;
  width: 100%;
}
