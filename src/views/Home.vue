<template>
  <div>
    <b-row>
      <b-container>
        <b-card-group deck>
          <b-card bg-variant=""
            header="รายการ"
            header-tag="header"
            footer="Card Food"
            footer-tag="footer"
          >
            <b-card-text>{{ food }}</b-card-text>
          </b-card>
        </b-card-group>
      </b-container> </b-row
    ><br /><br />
    <b-row>
      <b-container>
        <b-button href="/about" variant="outline-primary">ลองอีกครั้ง</b-button>
        &nbsp;
        <b-button href="//" variant="outline-primary">ออก</b-button>
      </b-container>
    </b-row>
  </div>
</template>
<script>
export default {
   props: {
     HelloWorld:String,
     food:String
   }
};
</script>
