<template>
<mdb-container>
    <mdb-card>
      <mdb-card-body>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  v-validate="'required'" name="Club" label="Club" outline />
          <div>{{ errors.first('Club') }}</div>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text" label="List" outline />
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Team" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Age-Group" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Full Name" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="CPR" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Email" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Phone" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Date Of Birth" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Country" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Foreignertiny" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Job" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Personal Image" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Registration_Type" required outline/>
         </mdb-col>
       </mdb-row>
        <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Registration Date" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Type" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Height" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Weight" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Season" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Year" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Medical Report" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="CPR-Certificate" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Passport" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Birth Certificate" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Resident Permit" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Resident Permit Guardian" required outline/>
         </mdb-col>
       </mdb-row>
       <mdb-row>
         <mdb-col col="5">
          <mdb-input type="text"  label="Registration Date" required outline/>
         </mdb-col>
         <mdb-col col="2"></mdb-col>
          <mdb-col col="5">
          <mdb-input type="text"  label="Type" required outline/>
         </mdb-col>
       </mdb-row>
      </mdb-card-body>
    </mdb-card>
</mdb-container>
</template>

<script>
import {
  mdbRow,
  mdbCol,
  mdbInput,
  mdbBtn,
  mdbCard,
  mdbCardBody,
  mdbContainer
} from 'mdbvue'
export default {
  name: 'Basic',
  components: {
    mdbInput,
    mdbBtn,
    mdbCard,
    mdbCardBody,
    mdbRow,
    mdbCol,
    mdbContainer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
