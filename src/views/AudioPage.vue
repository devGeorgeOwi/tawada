<template>
  <div class="animated fadeIn">
    <b-row>
      <b-col sm="6" md="4">
        <b-card >
          <b-form-group>
            <b-input-group>
              <b-form-input type="text" placeholder="Bookname"></b-form-input>
                <b-input-group-prepend>
                  <b-button variant="primary">
                    <i class="fa fa-search"></i>
                  </b-button>
                </b-input-group-prepend>
            </b-input-group>
          </b-form-group>
        </b-card>
      </b-col>
      <b-col sm="6" md="4">
        <b-card header="Recent Books">
          <div slot="header">
            <strong>Top</strong> Books
          </div>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>

<script>
import CardLine1ChartExample from './dashboard/CardLine1ChartExample'
import CardLine2ChartExample from './dashboard/CardLine2ChartExample'
import CardLine3ChartExample from './dashboard/CardLine3ChartExample'
import CardBarChartExample from './dashboard/CardBarChartExample'
import MainChartExample from './dashboard/MainChartExample'
import SocialBoxChartExample from './dashboard/SocialBoxChartExample'
import CalloutChartExample from './dashboard/CalloutChartExample'
import { Callout } from '@coreui/vue'

export default {
  name: 'audiopage',
  components: {
    
  },
  data: function () {
    return {
      
  }
  methods: {
    
    }
  }
}
</script>

<style>
  /* IE fix */
  #card-chart-01, #card-chart-02 {
    width: 100% !important;
  }
</style>
