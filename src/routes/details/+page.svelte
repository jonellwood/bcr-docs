<script>
    
    import details from "../../images/details-print-button.png";
    import moreButtons from "../../images/details-approve-deny-button.png";
    import buttonsCircles from "../../images/buttons-with-circles.png";
    import updated from "../../images/request-status-updated.png";
    import logs from "../../images/logs.png";
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
          <a href="/printing">print</a> requests.
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
        
      </div>
      <img src={moreButtons} alt="more button examples" width="80%" />
    </div>
    <hr>
    <div>
      <h3>Approving / Denying requests</h3>
      <p>If your role involves approving or denying requests you will have buttons for each request to take action</p>
      <figure>
        <figcaption>
          The logged in user is a Finance Approver and has options to Print the
          request, apply a Finance Approved status or Finance Denied status to the
          request.
        </figcaption>
        <img src={buttonsCircles} alt="Two buttons with colorful circles around them" width="90%"/>
      </figure>
      <figure>
        <img src={updated} alt="request card with Approved by Finance Status badge" />
        <figcaption>After applying a decision you will be redirected back to the Requests Dashboard and you will see the status badge updated to reflect the action you just took </figcaption>
      </figure>
      <hr>
      <div>
        <p>The action will also be logged in the system logs and be reflected in the details view of the request as well.</p>
        <img src={logs} alt="just some logs. Not the cool ones from trees but entries made into a logging system to keep track of events" width="100%"/>
      </div>
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
    a{
      text-decoration: none;
      cursor: pointer;
      /* color: #005677; */
      color: #58c9e8;
      font-weight: 400;

    }
    figure{
      display: grid;
      grid-template-columns: 1fr 1fr;
    }
    
  </style>
  