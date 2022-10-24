<script>
    
    import details from "../../images/details-print-button.png";
    import moreButtons from "../../images/details-approve-deny-button.png";
  </script>
  
  <div class='main'>
    <h1>Viewing Request Details</h1>
    <hr>
    <h3>Viewing the Details of a Request</h3>
    <div class="list-with-image">
      <img src={details} alt="details view" width="90%" />
      <div>
        <p>
          By selecting "details" from the dashbaord you can view the details of
          each request. In this example you can see that <mark
            ><b>"Jon Ellwood"</b></mark
          >
          is requesting <mark><b>"$1000"</b></mark> from moved from
          <mark><b>"Post it Notes" to "Coffee"</b></mark> from within the Auditor Department
          for a very silly reason.
        </p>
        <p>
          Based on your role in the system you will be presented with buttons that
          allow you to take action on the request.
        </p>
        <p>
          As you can see in this example - this user can only enter and view or
          print requests.
        </p>
      </div>
    </div>
    <hr>
    <div class="list-with-image">
      <div>
        <p>
          In this example we can see that Jerri Christmas is requesting $9,999 be
          moved from "Horseshoes to Horsehats from within the Animal Center
          becuase she needs more cowbell??
        </p>
        <p>
          The logged in user is a Finance Approver and has options to Print the
          request, apply a Finance Approved status or Finance Denied status to the
          request.
        </p>
      </div>
      <img src={moreButtons} alt="more button examples" width="80%" />
    </div>
  </div>
  
  <style>
    p {
      text-align: left;
    }
  
    .list-with-image {
      display: grid;
      grid-template-columns: 1fr 1fr;
    }
    img{
        margin: 20px;
    }
    .main{
        margin: 30px;
        max-width: 1080px;
    }
    
  </style>
  