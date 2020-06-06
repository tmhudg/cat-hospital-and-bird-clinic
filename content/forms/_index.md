---
title: "Forms"
date: 2018-04-30T20:12:35-04:00
draft: false
---

## This is a test


<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">

<form>
  <div class="form-group row">
    <label for="Client Name" class="col-4 col-form-label">Your Name</label> 
    <div class="col-8">
      <input id="Client Name" name="Client Name" type="text" class="form-control" required="required">
    </div>
  </div>
  <div class="form-group row">
    <label for="Pet Name" class="col-4 col-form-label">Pet's Name</label> 
    <div class="col-8">
      <input id="Pet Name" name="Pet Name" type="text" class="form-control">
    </div>
  </div>
  <div class="form-group row">
    <label for="Owned Duration" class="col-4 col-form-label">How long have you owned your cat</label> 
    <div class="col-8">
      <input id="Owned Duration" name="Owned Duration" type="text" class="form-control">
    </div>
  </div> 
  <div class="form-group row">
    <div class="offset-4 col-8">
      <button name="submit" type="submit" class="btn btn-primary">Submit</button>
    </div>
  </div>
</form>