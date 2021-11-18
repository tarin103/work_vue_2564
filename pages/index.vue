<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block"
        >
          <v-icon large color="blue" dark>
            mdi-cloud-upload
          </v-icon>
        </div>
      </v-col>
    </v-row>
    <h1 style="margin-top:20px;">
      TRS BANK
    </h1>
    <h3>MOBILE APP</h3>
    <v-row>
      <v-container>
        <v-form>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-menu transition="scroll-y-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="PLEASE ENTER YOUR PASSWORD"
                  placeholder="PASSWORD"
                  filled
                  rounded
                  dense
                  v-bind="attrs"
                  v-on="on"
                >
                  />
                </v-text-field>
              </template>
              <div class="box">
                <v-row>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      1
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      2
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      3
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      4
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      5
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      6
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      7
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      8
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      9
                    </v-btn>
                  </v-col>
                  <v-col class="d-flex justify-center ">
                    <v-btn
                      class="mx-3"
                      fab
                      dark
                      color="primary"
                    >
                      0
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="yellow"
                    >
                      x
                    </v-btn>
                  </v-col>
                </v-row>
              </div>
            </v-menu>
            <v-btn
              class="btn1"
            >
              <span class="txtt">LOGIN</span>
            </v-btn>
            <p>forgot password?</p>
            <p>new to bank app? sigh up</p>
          </v-col>
        </v-form>
      </v-container>
    </v-row>
  </div>
</template>
<style>
.pa-7{
  margin-top: 100px;
}
h3{
  margin-bottom: 50px;
}
.btn1{
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-bottom: 60px;
}
.box{
 background-color: white;
 padding: 5px;
 border-radius: 25px;
 font-size: 18px;
}
</style>