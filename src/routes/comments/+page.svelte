<script>
    import comments from "../../images/details-comments-and-logs.png";
    
</script>
<div class='main'>
    <h1>Using the Comments Feature</h1>
    <hr>
    <div class="list-with-image">
      <div>
        <h3>Adding and Reading Comments</h3>
        <p>
          Each request can have comments added it after being submitted. These
          comments are part of the permanent record of the request
        </p>
        <p>
          These comments can be used for adding notes regarding the request -
          perhaps you want to note that you denied the request becuase the amount
          requested exceeded the amount available in the account.
        </p>
    <hr>        
        <h3>Logging</h3>
        <p>
          You can also see in this example that each step of the process is logged
          with a date and time stamp aling with the user that initiated the action
        </p>
      </div>
      <img src={comments} alt="a look at comments" />
    </div>
  </div>
  <style>
    img{
        margin: 20px;
    }
    .main{
        margin: 30px;
        max-width: 1080px;
    }
  </style>
