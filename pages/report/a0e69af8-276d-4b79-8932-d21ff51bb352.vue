<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
require('@/static/bootstrap.theme.journal.min.css')
</script>

<template>
  <section>
    <div class="jumbotron jumbotron-fluid hero text-white mb-4">
        <div class="container">
            <h1 class="display-4">4845 Travertine Avenue</h1>
            <p class="lead">Pre-offer Inspection Report</p>
        </div>
    </div>
      <div class="container px-4 pb-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">98 / 100</strong>Overall Score</li>
              <li class="list-group-item"><strong class="float-right">Oct 10th, 2018</strong>Last Inspection Date</li>
              <li class="list-group-item"><strong class="float-right"><a href="https://pillartopost.com/" target="_block">Pillar to Post</a></strong>Last Inspection Provider</li>
              <li class="list-group-item"><strong class="float-right">1</strong>Previous Owners</li>
              <li class="list-group-item"><strong class="float-right">2013</strong>Constructed Year</li>
              <li class="list-group-item"><strong class="float-right">1911 ft<sup>2</sup></strong>Square Feet</li>
              <li class="list-group-item"><strong class="float-right">330 ft<sup>2</sup></strong>Attached Garage</li>
              <li class="list-group-item"><strong class="float-right">3</strong>Bedrooms</li>
              <li class="list-group-item"><strong class="float-right">3</strong>Full Baths</li>
              <li class="list-group-item"><strong class="float-right">1</strong>Half Baths</li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Overall Score Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 98 / 100</h5>
                <p class="card-text">The Travertine Avenue house is at a premium.  While there were some details missing from the initial inspection, they are minor and the property is in generally stellar condition.  The highest concern is the deck with some loose boards, but that's a minor repair that shouldn't take a huge amount of effort.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

    <div class="card text-center mb-4">
        <div class="card-body">
            <h5 class="card-title">Report Details</h5>
        </div>
    </div>

      <div class="container bg-info p-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">93 / 100</strong>Structural Systems</li>
              <li class="list-group-item"><strong class="float-right">Failed</strong>Balcony <p class="text-muted mb-0">Multiple loose boards are a tripping hazard.<br />The privacy railings nearest the building are loose and must be secured</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Foundation (type: poured)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Grading / Drainage</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Walls Exterior (type: vinyl siding)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Walls Interior <p class="text-muted mb-0">0.5 inch hole in front master bedroom</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Doors <p class="text-muted mb-0">Front exterior door hardware loose/damaged<br />Back master bathroom door hardware loose/damaged</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Windows (type: vinyl)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Driveway (type: concrete)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Roof (type: asphalt shingles)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Crawlspace <p class="text-muted mb-0">No crawlspace in this house</p></li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Structural Systems Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 93 / 100</h5>
                <p class="card-text">Most of the building appears to be structurally sound.  The balcony issues are relatively simple repairs.  The score is docked slightly due to the roofing and exterior windows/walls being inspected visually with binoculars.  Without physically being on the roof there are types of damage that are difficult to see</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container bg-light p-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">99 / 100</strong>Attic & Garage</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Access (ceiling hatch)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Insulation (type: blown, est. depth 13 inches)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Ventilation (type: ridge & soffit)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Sheathing (type: wood)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Garage door</li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Attic Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 99 / 100</h5>
                <p class="card-text">The attic is in pristine condition.  However, due to the blown insulation it is not possible to inspect some parts of it.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container bg-info p-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">97 / 100</strong>Electrical System</li>
              <li class="list-group-item"><i class="float-right">Concealed Wires</i>Limitations</li>
              <li class="list-group-item"><i class="float-right">120/240 Volts, 200 Amps</i>Service Size</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Distribution Panel</li>
              <li class="list-group-item"><strong class="float-right">Not Inspected</strong>Grounding<p class="text-muted">Further inspection is warranted to ensure proper grounding</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Smoke Alarms<p class="text-muted">Alarms on 1st, 2nd, and 3rd floors</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Carbon Monoxide Alarm<p class="text-muted">Alarm on 2nd floor</p></li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Electrical System Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 97 / 100</h5>
                <p class="card-text">There are no major concerns with the electrical systems but an inspection of grounding would be prudent.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container bg-light p-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active">Heating, Ventilation, and Air Conditioning (HVAC)<strong class="float-right">99 / 100</strong></li>
              <li class="list-group-item"><i class="float-right">Electric and Natural Gas</i>Energy Sources</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Thermostats (type: programmable)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Air Conditioning<p class="text-muted">Model: Trane, Manufactured: 2013<br />System lines and filter buried under mulch, needs minor servicing</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Furnace<p class="text-muted">Model: Trane, Manufactured: 2013</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Air Filters<p class="text-muted">3rd floor filter should be replaced</p></li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                HVAC Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 99 / 100</h5>
                <p class="card-text">Minor maintainence required around the air conditioning unit and the third floor air filter.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container bg-info p-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">100 / 100</strong>Plumbing System</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Water Pressure</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Water Main (type: plastic pipe)<p class="text-muted">Visible portion inspected</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Distribution Piping (type: plastic pipe)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Water Heating (type: tankless)<p class="text-muted">Model: Rheem, Manufactured: 2013</p></li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Hose Bibs</li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Plumbing System Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 100 / 100</h5>
                <p class="card-text">All plumbing systems passed.</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container bg-light p-4 mb-4">
        <div class="row">
          <div class="col-md-6">
            <ul class="list-group">
              <li class="list-group-item active"><strong class="float-right">100 / 100</strong>Appliances</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Refrigerator</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Oven/stove (type: glass top)</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Microwave</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Dishwasher</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Garbage Disposal</li>
              <li class="list-group-item"><strong class="float-right">Passed</strong>Washer/dryer</li>
            </ul>
          </div>
          <div class="col-md">
            <div class="card">
              <div class="card-header">
                Appliances Details
              </div>
              <div class="card-body">
                <h5 class="card-title">Score: 100 / 100</h5>
                <p class="card-text">All appliances passed.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="jumbotron jumbotron-fluid border-top mb-0 py-4 bg-secondary">
        <div class="container px-4">
            <p class="lead text-white">Questions?</p> <a href="mailto:" class="lead text-info">Contact us</a>
        </div>
    </div>
  </section>
</template>

<style>
/**
 * index.scss
 * - Add any styles you want here!
 */

body {
  background: #f5f5f5;
}

.hero {
  background-image: url('../../assets/images/ocean.jpg');
  background-repeat: no-repeat;
  background-size: cover;
}

.score-item {
  height: 38px;
}

.score-item-3 {
  height: 114px;
}
</style>
