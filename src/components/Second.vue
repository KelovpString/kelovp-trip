<template>
  <div class="page">
    <el-row>
      <el-col :span="6">
        <div class="sidebar">
          <div class="timeline">
            <h2>Timeline</h2>
            <ul>
              <timeline-item v-for="(item, index) in timeline" :key="index" :item="item" />
            </ul>
          </div>
        </div>
      </el-col>
      <el-col :span="18">
        <div class="body">
          <iframe class="fill" src="https://example.com"></iframe>
        </div>
      </el-col>
    </el-row>
  </div>
</template>

<style>
.fill {
  width: 100%;
  height: 100%;
  border: none;
}
</style>