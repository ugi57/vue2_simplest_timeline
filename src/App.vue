<template>
  <div class="timeline">
    <TimelineTime>2022</TimelineTime>
    <TimelineTitle>这里是标题</TimelineTitle>
    <TimelineItem>这里是内容</TimelineItem>
    <TimelineTitle>这里是标题sssssssssssssssssssssssssssssssssssssssssssssssssssssssssss</TimelineTitle>
    <TimelineItem>这里是内容ssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssssss</TimelineItem>
    <TimelineTime>2021</TimelineTime>
    <TimelineTitle>这里是标题</TimelineTitle>
    <TimelineItem>这里是内容</TimelineItem>
  </div>
</template>

<script>

import TimelineTime from './components/TimelineTime'
import TimelineTitle from './components/TimelineTitle'
import TimelineItem from './components/TimelineItem'

export default { 
  components: {
    TimelineTime,TimelineTitle,TimelineItem
  }
}
</script>

<style>
* {
  margin:0;
  padding:0;
  }

.timeline{
  padding:30px;
}

.timeline_time{
  font-weight:bold;
  text-align:left;
  font-size:20px;
  color:rgb(100, 100, 100);
}

.timeline_title{
  font-weight:bold;
  text-align:left;
  display:block;
  width:20%;
  margin:20px 0 10px 30px;
  color:rgb(100, 100, 100);
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
}

.timeline_content{
  text-align:left;
  display: block;
  margin:10px 0 20px 30px;
  height:70%;
  font-size:14px;
  color:rgb(100, 100, 100);
  width:30%;
  overflow:hidden;
  text-overflow:ellipsis;
  white-space:nowrap;
}
</style>