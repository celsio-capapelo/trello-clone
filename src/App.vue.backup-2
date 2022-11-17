<template>
  <!-- Sidebar START -->
  <TheSideBar />
  <!-- Sidebar END -->

    <!-- Navigation START -->
    <TheNavbar />
    <!-- Sidebar END -->

    <!-- Main content START -->
    <div class="app--1__3">
      <!-- Filters section START -->
      <section>
        <div class="filters">
          <div class="filters__left">
            <div class="">
              <button class=" btn btn--outline"><i class="sidebar__icon las la-chart-bar"></i></button>
              <button class=" btn btn--outline"><i class="sidebar__icon las la-align-justify"></i></button>
            </div>
            <button class="btn btn--deal btn--primary">
              <span>
                <i class="nav__icon--s las la-plus"></i>
              </span>
              <span>Deal</span>
            </button>
          </div>
          <div class="filters__right">
            <div class="">
              <i class="las la-dollar-sign nav__icon--s"></i>
              <span>507,705</span>
            </div>
            <div class="">
              <i class="las la-balance-scale-left nav__icon--s"></i>
              <span>507,705</span>
            </div>
            <div class="">
              <span>23 deals</span>
            </div>
          </div>
        </div>
      </section>
      <!-- Filters section END -->

      <!-- Stages section START -->
      <section class="stage__list">
        <div>
          <div class="stage__item">
            <p class="stage__text">Qualified Lead</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div class="stage__item">
            <p class="stage__text">Contact Made</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div class="stage__item">
            <p class="stage__text">Meeting Arranged</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div class="stage__item">
            <p class="stage__text">Needs Defined</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div class="stage__item">
            <p class="stage__text">Proposal Sent</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
        <div>
          <div class="stage__item">
            <p class="stage__text">Contract Sent</p>
            <div class="stage__summary">
              <div>
                <span><i class="las la-balance-scale-left stage__icon"></i></span>
                <span>$45,705</span>
              </div>
              <div class="">
                <span>23 deals</span>
              </div>
            </div>
          </div>
        </div>
       
      </section>
      <!-- Stages section END -->

      <!-- Deals section START -->
      <section class="deal__table">
        <DealList :deals="deals.leads" stage="leads"/>
        <DealList :deals="deals.contacts" stage="contacts"/>
        <DealList :deals="deals.meetings" stage="meetings"/>
        <DealList :deals="deals.needs" stage="needs"/>
        <DealList :deals="deals.proposals" stage="proposals"/>
        <DealList :deals="deals.contracts" stage="contracts"/>
      </section>
      <!-- Deals section END -->
    </div>
    <!-- Main content END -->
</template>

<style></style>

<script>
  import deals from './deals';
  import DealList from './components/DealList.vue';
  import TheSideBar from './components/TheSideBar.vue';
  import TheNavbar from './components/TheNavbar.vue';

  export default {
    components: {
      DealList,
      TheSideBar,
      TheNavbar,
    },
    created() {
      this.deals = deals;
    },
    data() {
      return {
        deals: null
      }
    },
  }
</script>