<template>
  <div id="dev-container">
    <dv-border-box-4 style="width:500px;height:300px;" backgroundColor="rgba(79, 210, 221, 0.3)" />
  </div>
</template>

<script>

export default {
  name: 'dev',
  data () {
    return {
      config: {
        digitalFlopToFixed: 2,
        data: [
            {
              name: '周口',
              value: 55
            },
            {
              name: '南阳',
              value: 120
            },
            {
              name: '西峡',
              value: 78
            },
            {
              name: '驻马店',
              value: 66
            },
            {
              name: '新乡',
              value: 80
            }
          ]
      }
    }
  }
}
</script>

<style lang="less">
#dev-container {
  width: 100%;
  height: 600px;
  box-shadow: 0 0 3px green;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #282c34;
  color: #fff;

  .dev {
    width: 300px;
    height: 200px;
  }
}
</style>
