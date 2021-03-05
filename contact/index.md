---
layout: layouts/post.njk
title: Contact
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 3
---
<div class="container">
  <div class="row">
    <form name="contact" method="POST" data-netlify="true">
    <div class="col">
        <label class="form-label">Your Name: <input type="text" name="name" class="form-control" required /></label>   
    </div>
    <div class="col">
        <label class="form-label" >Your Email: <input type="email" name="email" class="form-control" required/></label>
    </div>
    <div class="col">
        <label class="form-label" >Your Role: </label>
        <select name="role[]" class="form-select" required>
        <option value="leader" selected>Leader</option>
        <option value="follower">Follower</option>
        </select>
    </div>
    <div class="col">
        <label class="form-label" >Message: </label>
        <textarea name="message" class="form-control" rows="3"></textarea>
    </div>
    <div class="col">
        <button type="submit" class="btn btn-primary">Send</button>
    </div>
    </form>
  </div>
</div>