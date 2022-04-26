<template>
  <div>
    <b-nav align="right">
      <b-nav-item>
        <Button :title="list[0]"/>
      </b-nav-item>
      <b-nav-item>
        <Button :title="list[1]"/>
      </b-nav-item>
            <b-nav-item>
        <Button :title="list[2]"/>
      </b-nav-item>
            <b-nav-item>
        <Button :title="list[3]"/>
      </b-nav-item>
    </b-nav>
  </div>
</template>

<script>
import Button from './Button.vue'
export default {
  data() {
    return {
      list:['Home','Twitter','Tokenomics','Chart']
    }
  },
  components:{
    Button
  }
}
</script>