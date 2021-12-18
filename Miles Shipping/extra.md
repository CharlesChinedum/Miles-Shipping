<div class="container">
            <img class="ship img-responsive" src="Images/ship-image-5.jpg" alt="ship image">
            <div class="img-overlay">
                <button class="btn btn-success">Contact</button>
            </div>
        </div>
.ship {
    max-width: auto;
    height: auto;
}
body {
    background-image: url('images/ship-image-5.jpg');
}
bg-success
.about {
    padding-bottom: 13%;
}

 <div class="card text-white" style="width: auto">
        <img class="card-img-top" src="Images/image-4.png" alt="card image">
        <div class="card-img-overlay text-center">
            <h4 class="card-title">Our Services</h4>
            <p class="card-text text-warning"> At miles shipping We offer all kinds of shipping services<br>
            
            </p>
            <a href="#" class="btn btn-primary">Get Started</a>
        </div>
    </div>

    .card-img-top {
    height: 10%;
}

<form class="pt-3 form">
        <div class="row container-fluid">
            <div class="col-md-6">
                <input type="text" class="form-control" placeholder="First Name">
            </div>
            <div class="col-md-6">
                <input type="text" class="form-control" placeholder="Last Name">
            </div>
            <div class="form-group">
                <input type="email" class="form-control" placeholder="Enter Email">
                <small class="form-text">We will never share your email with another person</small>
            </div>
        </div>
    </form>

    <div class="row container-fluid">
            <div class="col-md-6">
                <input type="text" class="form-control" placeholder="First Name" id="firstname">
            </div>
            <div class="col-md-6">
                <input type="text" class="form-control" placeholder="Last Name" id="lastname">
            </div>

            <div class="card-deck" style="width: 300px;">
       <div class="card">
           <img src="Images/image-4 - Copy.png" class="card-img-top m-0 img-rounded" alt="card image">
           <div class="card-body">
               <h5 class="card-title">Our Services</h5>
               <p class="class-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                   Placeat fugiat sequi, eum repellendus incidunt laudantium 
                   cupiditate earum rerum dolore dolorum recusandae, itaque amet nihil alias. 
                   Temporibus consectetur corporis doloremque optio.</p>
           </div>
           <div class="card-footer">
               <small class="text-muted"> Footer </small>
           </div>

            <div class="footer container-fluid row">
                <p class="col-md-3">Miles Shipping</p>
            </div>

            <small class="sub-heading">Tested & Trusted!</small>

            <div class="img-overlay">
                <button action="contact.html" class="btn btn-md overlay text-white btn-1">GET STARTED</button>
            </div>

            .img-overlay {
    position: absolute;
    top: 20%;
    bottom: 0;
    left: 0;
    right: 0;
    text-align: center;
}

.img-overlay:before {
    content: ' ';
    display: block;
    /* adjust 'height' to position overlay content vertically */
    height: 50%;
}

.overlay {
    background-color: teal;
}

.overlay:hover {
    color: black;
}