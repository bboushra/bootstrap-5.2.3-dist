<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="EX5.css">
  <link rel="stylesheet" href="bootstrap.min.css">
  <title>Formulaire Bootstrap</title>
</head>
<body>

  <div class="container">
    <div class="row">
      <div class="col-sm">
      </div>
      <div class="col-sm bg-light">
        <form>
          <div class="row">
            <div class="col">
            <label for="validationTooltip04">full name:*</label>
            <input type="full name:*" class="form-control" id="validationTooltip04" placeholder="full name" required>
          </div>
          <div class="col">
            <label for="validationTooltip04">last name:*</label>
            <input type="laste name:*" class="form-control" id="validationTooltip04" placeholder="last name" required>
          </div>
          </div>
         <div class="row">
          <div class="col">
          <label for="validationTooltip04">Email:*</label>
          <input type="Email:*" class="form-control" id="validationTooltip04" placeholder="Email" required>
        </div>
        <div class="col">
        <div class="col">
          <label for="validationTooltip04">phone number:*</label>
          <input type="phone number:*" class="form-control" id="validationTooltip04" placeholder="phone number" required>
        </div>
      </div>
    </div>
    <br>
    <label for="contact reason">contact reason:*</label>
       <select class="form-select">
        <option selected>select</option>
        <option value="1">Info</option>
        <option value="2">Design</option>
        <option value="3">Langues</option>
    </select>
    <div class="form-group">
      <label for="message">Message :</label>
      <textarea class="form-control" id="message" rows="4" placeholder="message" required></textarea>
    </div>
    <br>
    <button type="submit" class="btn btn-primary">submit</button>
  </form>
</div>
    
      <div class="col-sm">
</div>
</div>

</body>
</html>
