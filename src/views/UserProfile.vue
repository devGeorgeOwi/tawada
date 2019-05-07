<template>
  <div class=" animated fadeIn ">
    <b-row>
      <b-col md="6">
        <b-card class="mx-0 my-0 ">
          <div slot="header">
            <strong>Edit User</strong> Details
          </div>
          <b-form>
          <b-form-group
            description="Let us know your full name."
            label="Enter your name"
            label-for="basicName"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicName" type="text" autocomplete="name"></b-form-input>
          </b-form-group>
          <b-form-group
            label="Textarea"
            label-for="basicTextarea"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicTextarea" :textarea="true" :rows="9" placeholder="Content.."></b-form-input>
          </b-form-group>
          </b-form>
       </b-card>   
    </b-col>
  </b-row>
  </div>
</template>

<script>
// import Avatar from '@/views/components/Avatar'

export default {
  name: 'UserProfile'
}
</script>

<!--<style lang="scss">
  @import "../node_modules/@syncfusion/ej2-base/styles/material.css";
  @import "../node_modules/@syncfusion/ej2-layouts/styles/material.css";
</style> -->
