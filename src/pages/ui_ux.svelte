<script>

</script>
<main>
  <div class="left-corner-gradient"></div>
  <div class="background-layer"></div>
  <div class="right-corner-gradient"></div>

  <div class="ui-container">
    <div class="left-content">
      <div class="description">
        <h3>Plant Lover</h3>
        <p>
          A platform to get information on how to care for your houseplants,
          which you can then share with your neighbors so you can go on vacation knowing your garden
          is well taken care of.
        </p>
      </div>
      <img class="visual" src="/assets/visual.png" alt="Plant Lover Visual">
      <div class="color-palette">
        <div class="color light-green"></div>
        <div class="color teal"></div>
        <div class="color dark-green"></div>
        <div class="color grey"></div>
        <div class="color beige"></div>
      </div>
      <div class="fonts">
        <span class="font-description">Wire one</span><span class="wire-one">Plant Lover</span><br>
        <span class="font-description">Corbel</span><span class="corbel">Monstera Deliciosa</span>
      </div>
    </div>
    <div class="right-content">
      <div class="screens">
        <img class="cover" src="/assets/cover.png" alt="Plant Lover Cover Screen">
        <img class="overview" src="/assets/overview.png" alt="Plant Lover Garden Overview">
        <img class="detail" src="/assets/detail.png" alt="Plant Lover Plant Detail View">
        <img class="dashboard" src="/assets/dashboard.png" alt="Plant Lover Dashboard">
      </div>
      <div class="mockup-container">
        <img class="mockup" src="/assets/mockup.png" alt="Plant Lover Mockup">
      </div>
    </div>
  </div>
</main>
<style>

  p {
    color: #6E6E6E;
  }

  .ui-container {
    padding: 0 5rem;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
  }

  .left-content {
    width: calc(33% - 5rem);
    margin: 0 1rem;
  }

  .right-content {
    width: calc(66% - 5rem);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  .color-palette {
    display: flex;
    flex-direction: row;
  }

  .color:first-child {
    margin: .5rem .5rem .5rem 0;
  }

  .color {
    width: 50px;
    height: 50px;
    border-radius: 10px;
    margin: .5rem;
    box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
    -webkit-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
    -moz-box-shadow: 10px 10px 21px 1px rgba(0,0,0,0.1);
  }

  .light-green {
    background-color: #E0F2E7;
  }

  .teal {
    background-color: #7CA29C;
  }

  .dark-green {
    background-color: #497373;
  }

  .grey {
    background-color: #848484;
  }

  .beige {
    background-color: #FCFAF2;
  }

  .visual {
    width: 90%;
    max-width: 400px;
    border-radius: 10px;
    height: auto;
    margin: 1rem 0;
    box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
    -webkit-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
    -moz-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.2);
  }

  .fonts {
    margin: 2rem 0;
  }

  .font-description {
    font-size: 20px;
    margin-right: 1rem;
    text-align: center;
  }

  .wire-one {
    font-family: 'Wire One';
    font-size: 32px;
    color: #497373;
    letter-spacing: 1px;
  }

  .corbel {
    font-family: 'Corbel';
    font-size: 32px;
    color: #497373;
  }

  .screens {
    position: relative;
    margin-top: 3.5rem;
    margin-right: 3rem;
    width: 50%;
  }

  .cover, .overview, .dashboard, .detail {
    height: auto;
    width: 60%;
    max-width: 250px;
    position: absolute;
    border-radius: 10px;
    box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);
    -webkit-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);
    -moz-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);
  }

  .cover {
    left: 0;
    top: 0;
  }

  .overview {
    left: 50px;
    top: 25px;
  }

  .detail {
    left: 100px;
    top: 50px;
  }

  .dashboard {
    left: 150px;
    top: 75px;
  }

  .mockup-container {
    width: 50%;
  }

  .mockup {
    border-radius: 10px;
    width: 90%;
    max-width: 400px;
    height: auto;
    margin-top: 3.5rem;
    float: right;
    box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);
    -webkit-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);
    -moz-box-shadow: 10px -10px 21px 1px rgba(0,0,0,0.1);

  }

  @media screen and (max-width: 1024px) {
    .ui-container {
      flex-direction: column;
      }

    .left-content, .right-content {
      width: 100%;
    }
  }

</style>