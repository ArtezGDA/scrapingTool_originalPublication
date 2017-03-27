[![Screenshot01](images/Screenshot01.png)]
[![Screenshot02](images/Screenshot02.png)]
[![Screenshot03](images/Screenshot03.png)]
[![Screenshot04](images/Screenshot04.png)]

<!DOCTYPE html>
<html>
<head>
	<title>Schets pop-up</title>
	<style type="text/css">

	img {
    display: block;
    margin: auto;
    width: 40%;
}

	img:hover {
    opacity: 0.5;
}
		/* The Modal (background) */
		/* Modal Header */
.modal-header {
    padding: 2px 16px;
    /*background-color: #5cb85c;*/
    font-family: BodegaSerif;
    color: white;
    /*opacity: 0.5;*/
}

/* Modal Body */
.modal-body {
	padding: 2px 16px;
	color: white;
	font-family: BodegaSerif;
}


/* Modal Footer */
.modal-footer {
    padding: 2px 16px;
    /*background-color: #5cb85c;*/
    color: white;
    /*opacity: 0.5;*/
    font-family: BodegaSerif;
}

/* Modal Content */
.modal-content {
    position: relative;
    background-color: rgb(36,101,127);
    margin: auto;
    padding: 0;
    border: 1px solid #888;
    width: 80%;
    box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2),0 6px 20px 0 rgba(0,0,0,0.19);
    -webkit-animation-name: animatetop;
    -webkit-animation-duration: 0.4s;
    animation-name: animatetop;
    animation-duration: 0.4s
    opacity: 0.5;
    filter: alpha(opacity=60);
}

/* Add Animation */
@-webkit-keyframes animatetop {
    from {top: -300px; opacity: 0}
    to {top: 0; opacity: 1}
}

@keyframes animatetop {
    from {top: -300px; opacity: 0}
    to {top: 0; opacity: 1}
}
		.modal {
		    display: none; /* Hidden by default */
		    position: fixed; /* Stay in place */
		    z-index: 1; /* Sit on top */
		    left: 0;
		    top: 0;
		    width: 100%; /* Full width */
		    height: 100%; /* Full height */
		    overflow: auto; /* Enable scroll if needed */
		    background-color: rgb(36,101,127); /* Fallback color */
		    background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
		    opacity: 0.8;
		}

		/* Modal Content/Box */
		.modal-content {
		    background-color: rgb(36,101,127);
		    margin: 15% auto; /* 15% from the top and centered */
		    padding: 20px;
		    border: 1px solid #888;
		    width: 80%; /* Could be more or less, depending on screen size */
		}

		/* The Close Button */
		.close {
		    color: #aaa;
		    float: right;
		    font-size: 28px;
		    font-weight: bold;
		}

		.close:hover,
		.close:focus {
		    color: black;
		    text-decoration: none;
		    cursor: pointer;
		}
	</style>

</head>
<body>
	<!-- Trigger/Open The Modal -->
	<img id="myBtn" src="saved_resource(1)">
	<!-- <button id="myBtn">Open Modal</button> -->

	<!-- The Modal -->
	<div id="myModal" class="modal">

<div class="modal-content">
  <div class="modal-header">
    <span class="close">&times;</span>
    <h2>Information</h2>
  </div>
  <div class="modal-body">
    <p>CLUSTER GRAPHICS</p>
    <p>Bron: uk.reuters.com</p>
    <p>First published: 11-03-2017</p>
    <p>Author: Dylan Martinez</p>
  </div>
  <div class="modal-footer">
    <h6>MARLOU, ILSE, ZSA ZSA, SHARON</h6>
  </div>
</div>
	<script type="text/javascript">
			// Get the modal
		var modal = document.getElementById('myModal');

		// Get the button that opens the modal
		var btn = document.getElementById("myBtn");

		// Get the <span> element that closes the modal
		var span = document.getElementsByClassName("close")[0];

		// When the user clicks on the button, open the modal
		btn.onclick = function() {
		    modal.style.display = "block";
		}

		// When the user clicks on <span> (x), close the modal
		span.onclick = function() {
		    modal.style.display = "none";
		}

		// When the user clicks anywhere outside of the modal, close it
		window.onclick = function(event) {
		    if (event.target == modal) {
		        modal.style.display = "none";
		    }
		}
	</script>
</body>
</html>
