# 圆圈颜色

- order: 1

圆圈颜色。

---

````jsx
let Timeline = antd.Timeline;
let container = document.getElementById('components-timeline-demo-color');

React.render(
<Timeline>
  <Timeline.Item color="green">创建服务现场 2015-09-01</Timeline.Item>
  <Timeline.Item color="green">创建服务现场 2015-09-01</Timeline.Item>
  <Timeline.Item color="red">
    <p>初步排除网络异常1</p>
    <p>初步排除网络异常2</p>
    <p>初步排除网络异常3 2015-09-01</p>
  </Timeline.Item>
  <Timeline.Item>
    <p>技术测试异常1</p>
    <p>技术测试异常2</p>
    <p>技术测试异常3 2015-09-01</p>
  </Timeline.Item>
</Timeline>
, container);
````