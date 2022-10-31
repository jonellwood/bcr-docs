<script>
     import showingNew from "../../images/admin-dashboard-showing-new.png";
     import aDash from "../../images/admin-dashboard.png";
    import nav from "../../images/dashboard-just-nav.png";
    import buttons from "../../images/requests-show-all-and-activity.png";
    import all from "../../images/requests-showing-all.png";
</script>

<div class='main'>
    <h1>Using Your Requests Dashboard</h1>
    <hr>
    <!-- <h2>Upon successful log in you will see your dashbaord.</h2> -->
    <p>
      Your Requests Dashboard is intended to give you quick and accurate information about the status of requests in your queue.
    </p>
    <img src={nav} alt="nav example" />
    <h3>
      The dashboard will show requests related to your user account and role
      within the system.
    </h3>
    <div class="list-with-image">
      <ul>
        <li>It will <b>ALWAYS</b> show requests that you have submitted.</li>
        <li>
          If you are a Finance Approver it will show all requests where the
          Department is one you are responsible for.
        </li>
        <li>
          If you are an Administative Approver it will show <em>only</em> requests
          where the Departemnt is one you are responsible for <b>AND</b> Finance
          has already made an Approve or Deny decision regarding the Request.
          <ul>
            <li>
              As an Administrative Approver there will be an additional button
              available to "Show All" requests in the system without regard to
              Department or Status
            </li>
          </ul>
        </li>
        <li>
          Any requests <em>created</em> after the last time you logged into the application
          will have a "NEW" badge applied to it.
        </li>
        <li>
          The status badge in the right hand corner will quickly tell you the
          current status of the request
        </li>
      </ul>
      <img src={showingNew} alt="dashboard" width="100%" />
    </div>
    <hr>
    <div>
      <h3>Recent Activity</h3>
      <p>Below the request cards there is a "Recent Activity" button. Using this button will open a small window to show the last 10 logged events relevent to your users account. i.e. something YOU did, something SOMEONE else did to one of your requests, or something someone did with a request in a department associated with your user account.</p>
      <img src={buttons} alt="two buttons with text" />
      <h3>Conditional Access</h3>
      <p>If your user account has the permissions to allow it - there will be a "Show All" button under the request cards. This will remove all filters and show every request in the system without regard to status, department, or user. The large highlighted warning should serve as a reminder you are accessing all requsts in the system. Not just yours.</p>
      <img src={all} alt="page showing all requests with big yellow warning" />
    </div>
  </div>
  
  <style>
    
    ul {
      text-align: left;
    }
    .list-with-image {
      display: grid;
      grid-template-columns: 1fr 1fr;
    }
    img{
        margin: 20px;
    }
    :global(.inactive) {
      display: none;
    }
    :global(.active) {
      display: block;
    }
    .main{
        margin: 30px;
        max-width: 1080px;
    }
  </style>
  