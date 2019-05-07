<template>
  <div class="faded animated">
    <b-row>
      <b-col md="6">
        <b-card>
          <div slot="header">
            <strong>Create a user profile</strong>
          </div>
          <b-form>
          <b-form-group
            description="Let us know your full name."
            label="FullName"
            label-for="basicName"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicName" type="text" autocomplete="name"></b-form-input>
          </b-form-group>
          <b-form-group
            description="This is a help text"
            label="Text Input"
            label-for="basicText"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicText" type="text" placeholder="Text"></b-form-input>
          </b-form-group>
          <b-form-group
            label="Date" label-for="date"
            :label-cols="3"
            :horizontal="true">
            <b-form-input type="date" id="date"></b-form-input>
          </b-form-group>
          <b-form-group
            description="Please enter your email"
            label="Email Input"
            label-for="basicEmail"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicEmail" type="email" placeholder="Enter your email" autocomplete="email"></b-form-input>
          </b-form-group>
          <b-form-group
            description="Please enter a complex password"
            label="Password Input"
            label-for="basicPassword"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicPassword" type="password" placeholder="Enter your password" autocomplete="current-password"></b-form-input>
          </b-form-group>
          <b-form-group
            label="Textarea"
            label-for="basicTextarea"
            :label-cols="3"
            :horizontal="true">
            <b-form-input id="basicTextarea" :textarea="true" :rows="9" placeholder="Content.."></b-form-input>
          </b-form-group>
          <b-form-group
            label="Select"
            label-for="basicSelect"
            :label-cols="3"
            :horizontal="true">
            <b-form-select id="basicSelect"
              :plain="true"
              :options="['Please select','Option 1', 'Option 2', 'Option 3']"
              value="Please select">
            </b-form-select>
          </b-form-group>
          </b-form>
        </b-card>
      </b-col>
    </b-row>
  </div>
</template>
