---
layout: page
title: Contact
permalink: /contact/
---

<form class="form-horizontal" role="form" method="post" action="https://getsimpleform.com/messages?form_api_token=66fbee9ab3ce6ef1d615305d340a34b2">

	<input type='hidden' name='redirect_to' value='{{ site.baseurl }}/thank-you.html' />

    <div class="form-group">
        <label for="name" class="col-sm-2 control-label">Name</label>
        <div class="col-sm-10">
            <input type="text" class="form-control" id="name" name="name" placeholder="First & Last Name" value="">
        </div>
    </div>
    <div class="form-group">
        <label for="email" class="col-sm-2 control-label">Email</label>
        <div class="col-sm-10">
            <input type="email" class="form-control" id="email" name="email" placeholder="example@domain.com" value="">
        </div>
    </div>
    <div class="form-group">
        <label for="message" class="col-sm-2 control-label">Message</label>
        <div class="col-sm-10">
            <textarea class="form-control" rows="4" name="message"></textarea>
        </div>
    </div>
    <div class="form-group">
        <div class="col-sm-10 col-sm-offset-2">
            <input id="submit" name="submit" type="submit" value="Send Message" class="btn btn-primary">
        </div>
    </div>
</form>