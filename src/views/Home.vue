<template>
    <v-container fluid>
      <v-slide-y-transition mode="out-in">
        <v-layout column align-center>
          <v-flex xs12 sm6 offset-sm3>
            <v-hover>
              <v-card
                slot-scope="{ hover }"
                :class="`elevation-${hover ? 20 : 2}`"
                class="mx-auto"
                width="344"
              >
                <v-img
                  src="http://static.wixstatic.com/media/8eec17_d94aabd3acff4bff8a6c0ec48afdadbf.gif"
                  aspect-ratio="1.5"
                ></v-img>
                <v-card-title primary-title>
                  <div>
                    <h3 class="headline mb-0">Animation</h3>
                    <div>여기는 성경이의 홈페이지입니다.<br></div>
                  </div>
                  <v-card-actions>
                    <v-btn flat color="blue">로그인</v-btn>
                    <v-btn flat color="blue" >
                          로그아웃!
                   </v-btn>
                  </v-card-actions>
                </v-card-title>
              </v-card>
            </v-hover>
          </v-flex>
        </v-layout>
      </v-slide-y-transition>
    </v-container>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
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
