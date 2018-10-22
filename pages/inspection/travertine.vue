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
  <div class="jumbotron jumbotron-fluid hero text-white">
    <div class="container">
      <h1 class="display-4">Pre-offer Inspection Report</h1>
      <p class="lead">Peace of mind.</p>
    </div>
  </div>
  <div class="container bg-light p-4">
    <div class="row">
      <div class="col-sm mb-2">
        <h3 class="text-muted">Report for:</h3>
        <h2>4845 Travertine Avenue</h2>
        <h4>Virginia Beach, VA 12345</h4>
        <hr />
        <div class="mb-2">
          <h2 class="float-left mr-2">Overall Score</h2>
           <button type="button" class="btn btn-success score-item disabled">
            Very Good <span class="badge badge-light">98 / 100</span>
            <span class="sr-only">overall score 98 / 100</span>
          </button>
        </div><br />
        <div class="mb-2">
           <button type="button" class="btn btn-outline-primary score-item">
            Purchase Full Report
            <span class="sr-only">purchase full report</span>
          </button>
        </div>
      </div>
      <div class="col-sm">
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img class="d-block w-100" src="https://images.unsplash.com/photo-1502097250391-24b1392e5826?ixlib=rb-0.3.5&q=85&fm=jpg&crop=entropy&cs=srgb&ixid=eyJhcHBfaWQiOjE0NTg5fQ&s=90a67a0f59a8f2c4df0d7d70a813d4d1" alt="First slide">
            </div>
            <div class="carousel-item">
              <img class="d-block w-100" src="https://images.unsplash.com/photo-1461963040894-7ee721035376?ixlib=rb-0.3.5&q=85&fm=jpg&crop=entropy&cs=srgb&ixid=eyJhcHBfaWQiOjE0NTg5fQ&s=58cf735ba5d58d7bebfe12f3924e1c6f" alt="Second slide">
            </div>
            <div class="carousel-item">
              <img class="d-block w-100" src="https://images.unsplash.com/photo-1511995228778-b6d4d546a672?ixlib=rb-0.3.5&q=85&fm=jpg&crop=entropy&cs=srgb&ixid=eyJhcHBfaWQiOjE0NTg5fQ&s=7ac99a99a9ad1bd86ab4650af44bf4de" alt="Third slide">
            </div>
          </div>
          <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </div>


<div class="card text-center">
  <div class="card-body">
    <h5 class="card-title">Some kind of marketing</h5>
    <p class="card-text">The scores below are a compilation of information from places.</p>
  </div>
</div>


  <div class="container bg-light p-4 mb-4">
    <div class="row">
      <div class="col-sm">
        <div class="d-flex justify-content-end mb-2">
          <button type="button" class="btn btn-success float-right score-item disabled">
            Very Good <span class="badge badge-light">98 / 100</span>
            <span class="sr-only">Overall Score 98 / 100</span>
          </button>
        </div>

        <div class="d-flex justify-content-end mb-2">
          <button type="button" class="btn btn-warning float-right score-item disabled">
            Good <span class="badge badge-light">87 / 100</span>
            <span class="sr-only">Foundational Systems 87 / 100</span>
          </button>
        </div>

        <div class="d-flex justify-content-end mb-2">
          <button type="button" class="btn btn-success float-right score-item disabled">
            Very Good <span class="badge badge-light">98 / 100</span>
            <span class="sr-only">Plumbing 98 / 100</span>
          </button>
        </div>

        <div class="d-flex justify-content-end align-items-center mb-2 score-item-3">
          <div class="mr-2"><h3 class="text-muted">Want more?</h3></div>
          <div><button type="button" class="btn btn-outline-primary">Purchase Report</button></div>
        </div>
</div>


      <div class="col-sm">
        <div class="mb-2 score-item d-flex align-items-center">
          <h2><div>Overall Score</div></h2>
        </div>

        <div class="mb-2 score-item d-flex align-items-center">
          <div><a href="#" class="text-primary" data-toggle="modal" data-target="#foundationalModal">Foundational Systems</a></div>
        </div>

        <div class="mb-2 score-item d-flex align-items-center">
          <div><a href="#" class="text-primary" data-toggle="modal" data-target="#plumbingModal">Plumbing</a></div>
        </div>

        <div class="mb-2 score-item d-flex align-items-center">
          <div><a href="#" class="text-primary" data-toggle="modal" data-target="#exampleModalCenter">HVAC</a></div>
        </div>

        <div class="mb-2 score-item d-flex align-items-center">
          <div><a href="#" class="text-primary" data-toggle="modal" data-target="#exampleModalCenter">Electrical</a></div>
        </div>

        <div class="mb-2 score-item d-flex align-items-center">
          <div><a href="#" class="text-primary" data-toggle="modal" data-target="#exampleModalCenter">Additional Information</a></div>
        </div>
      </div>
    </div>
  </div>


  <div class="container p-0 mb-4">

      <div class="card">
        <h5 class="card-header">Some additional Info</h5>
        <div class="card-body">
          <h5 class="card-title">Marketing!</h5>
          <p class="card-text">Natural lead in to additional marketing.</p>
          <a href="#" class="btn btn-primary">View Sample Report</a>
        </div>
      </div>
  </div>

    <div class="jumbotron jumbotron-fluid border-top mb-0 py-4 bg-secondary">
        <div class="container px-4">
            <p class="lead text-white">Questions?</p> <a href="mailto:" class="lead text-info">Contact us</a>
        </div>
    </div>

<!-- Modal -->
<div class="modal fade" id="exampleModalCenter" tabindex="-1" role="dialog" aria-labelledby="exampleModalCenterTitle" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalCenterTitle">Overall Score</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        Lorem Ipsum
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>


<div class="modal fade" id="foundationalModal" tabindex="-1" role="dialog" aria-labelledby="foundationalModal" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalCenterTitle">Foundational Systems</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <ul>
          <li>Ceilings and Floors</li>
          <li>Walls and doors</li>
          <li>Foundation</li>
          <li>Grading and Drainage</li>
        </ul>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>


<div class="modal fade" id="plumbingModal" tabindex="-1" role="dialog" aria-labelledby="plumbingModal" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered" role="document">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalCenterTitle">Plumbing Modal</h5>
        <button type="button" class="close" data-dismiss="modal" aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </div>
      <div class="modal-body">
        <ul>
          <li>Toilets</li>
          <li>Water Pressure</li>
          <li>Showers</li>
        </ul>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
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
  background-image: url(https://images.unsplash.com/photo-1537902681360-cee1e4f5206b?ixlib=rb-0.3.5&q=85&fm=jpg&crop=entropy&cs=srgb&ixid=eyJhcHBfaWQiOjE0NTg5fQ&s=b702b75550ef66b8f5a5c05e6e071da6);
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
