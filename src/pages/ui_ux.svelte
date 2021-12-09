<script>
  import Image from "../components/image.svelte";

  const visualName = 'visual';
  const visualAlt = 'Plant Lover Visual';

  const coverName = 'cover';
  const coverAlt = 'Plant Lover Cover Screen';

  const overviewName = 'overview';
  const overviewAlt = 'Plant Lover Garden Overview';

  const detailName = 'detail';
  const detailAlt = 'Plant Lover Plant Detail View';

  const dashboardName = 'dashboard';
  const dashboardAlt = 'Plant Lover Dashboard';

  const mockupName = 'mockup';
  const mockupAlt = 'Plant Lover Mockup';

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
        <Image className={visualName} fileName={visualName} alt={visualAlt} />
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
        <Image className={coverName} fileName={coverName} alt={coverAlt} />
        <Image className={overviewName} fileName={overviewName} alt={overviewAlt} />
        <Image className={detailName} fileName={detailName} alt={detailAlt} />
        <Image className={dashboardName} fileName={dashboardName} alt={dashboardAlt} />
      </div>
      <div class="mockup-container">
        <Image className={mockupName} fileName={mockupName} alt={mockupAlt} />
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
    margin: .5rem;
    border-radius: 10px;
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


  .mockup-container {
    width: 50%;
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