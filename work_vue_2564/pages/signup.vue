<template>
  <div class="rounded-xl text-center white">
    <p class="txt1">
      Sign up your bank account
    </p>
    <v-form>
      <v-container>
        <v-text-field
          label="Your Name"
          outlined
          dense
        />
        <v-text-field
          label="Bank Account"
          outlined
          dense
        />
        <v-text-field
          label="Mobile phone number"
          outlined
          dense
        />
        <v-text-field
          label="Email"
          outlined
          dense
        />
        <v-text-field
          label="Password"
          outlined
          dense
        />
        <p class="txt2">
          Use 6 characters with a mix of numbers
          and letters
        </p>
        <v-checkbox
          label="John"
          value="John"
        >
          <span style="color:black">test</span>
        </v-checkbox>
      </v-container>
    </v-form>
  </div>
</template>

<style>
  .txt1{
    color: #5462ff;
    padding-top: 20px;
  }
  .txt2{
    color: #5462ff;
    font-size: 8px;
  }
  .v-text-field--outlined fieldset {
    color: #95a0ef !important;
    height: 40px;
}
.v-checkbox{
  color:#95a0ef;
}

</style>
