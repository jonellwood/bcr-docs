<script>
    import newRequestMain from "../../images/user-enter-new-request.png";
    import changeDepartment from "../../images/user-enter-change-department.png";
    import changeObject from "../../images/user-enter-new-request-account-select.png";
    import addLineItem from "../../images/add-line-item-annotated.png";
    import over10 from "../../images/user-enter-new-request-over-10k.png";
    import addJustification from "../../images/user-enter-new-request-add-justification.png";
    
  </script>
  
  <div class='main'>
    <h1>Entering a New Request</h1>
    <hr>
    <h2>
      To enter a new request select "New Request" from the Navigation bar on the
      top of the page
    </h2>
    <div>
      <h3>The new request page will load</h3>
  
      <p>
        Many users have several Departments the are responsible for entering
        requests for. Your "Default Department" will be automatically loaded for
        you. This default can be changed if needed by entering a request via
        support ticket
      </p>
      <img src={newRequestMain} alt="New Request Dashboard" />
      <hr>
      <div class="list-with-image">
        <p>
          You can also change what department you are entering the request for by
          using the "Change Department" button. A slide out will open up and allow
          you to select from a list of your assigned departments.
        </p>
        <img src={changeDepartment} alt="Showing the change department option" />
      </div>
      <hr>
      <h3>Selecting <b>TO</b> and <b>FROM </b>objects</h3>
      <div class="list-with-image">
        <img src={changeObject} alt="Dropdown to change object" width="90%" />
        <p>
          The <em>to</em> and <em>from </em>options are loaded each time the
          Department is selected. To select what object you wish to move mone from
          use the dropdown to select from the available options
        </p>
      </div>
      <hr>
      <h3>Enter the Amount to be moved</h3>
      <div class="list-with-image">
        <div>
          <p>
            After selecting the to and from objects you will enter an amount to be
            transfered.
          </p>
  
          <p>
            <b
              >AFTER entering the amount Press TAB to move the focus from the
              input box</b
            >
          </p>
          <p>
            After tabbing from the input you will notice the "+ Add Line Item +"
            button is now activated. <i>IF</i> you wish to add a second line item to
            the request use the Add Line Item button and an additional line item will
            be added to the form.
          </p>
          <p>
            If you wish to remove the line item use the "- Remove Line Item -"
            button
          </p>
          <p>Requests should be limited to 10 line items per request</p>
          <p>
            You will notice the <b>TOTAL</b> amount in the green box updates as you
            add money to the request. Pretty cool huh? :)
          </p>
        </div>
        <img src={addLineItem} alt="add line item" width="90%" />
      </div>
      <div>
        <hr>
        <h3>Request Limits</h3>
        <p>
          Requests are currently limited to a total of $10,000. If you enter an
          amount over $10,000 the system will let you know
        </p>
        <img src={over10} alt="warning about $10,000 limit" />
        <p>Use the "RESET" button to start over</p>
      </div>
      <div>
        <hr>
        <h3>Request Justification</h3>
        <div class="list-with-image">
          <div>
            <p>
              After entering the request details you will enter the reason for the
              request. This should provide enough information to the person(s)
              evaluating the request to understand the reason behind the request
              and what has triggered the need for it. Be verbouse.
            </p>
            <p>
              After entering your request justification press <b><em>TAB</em></b> to
              move the focus from that input. You will notice the "Submit" button is
              now active and you are able to submit your request to the system.
            </p>
            <p>
              Upon successful submittal you will be redirected back to your
              dashboard where you will see your request with a "NEW" badge applied
              to it.
            </p>
          </div>
          <img
            src={addJustification}
            alt="adding request justification"
            width="80%"
          />
        </div>
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
    
  </style>
  