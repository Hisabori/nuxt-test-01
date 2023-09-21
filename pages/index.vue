<template>
  <div>
    <h1>spa 방식임</h1>
    <p>이거 spa 방식으로 돌아감</p>

    <!--오늘 날짜-->
    <p>오늘 {{Today}}임...</p>
  </div>
</template>

<script>
//import moment

import moment from 'moment';


export default {
  name:  'Index'

  //data.return
  data() {
    return{
      today: moment().format('DD-MM-YYYY'),
    };
  },
};
</script>
