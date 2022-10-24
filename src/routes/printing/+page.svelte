<script>
    import printing from "../../images/print-button-annotated.png";
    import printPreview from "../../images/details-print-button-results.png";
    import printSelect from "../../images/details-print-button-results-printer-select.png";
  </script>
  
  <div class='main'>
    <h1>Printing a Request on Paper</h1>
    <hr>
    <div class="list-with-image">
      <div>
        <h3>Printing to Paper</h3>
        <p>
          While the main idea of an application like this is to reduce paper use,
          there may be a situation where it is required. In the details screen
          there is a "Print" button that will open up a preview of the request.
        </p>
      </div>
      <img src={printing} alt="print button" />
    </div>
    <div class="list-with-image">
      <img src={printPreview} alt="print preview" width="75%" />
      <div>
        <p>
          Using the "Print Button" will open up preview of the document along with
          a small print button at the bottom of the page.
        </p>
        <p>
          Using this print button will open the native Printer / Option select
          window and allow you to select a printer along adjust settings such as
          margins, color or B/W, and Duplexing
        </p>
        <img src={printSelect} alt="Select a printer" width="80%" />
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
  