<template>
  <div class="indexView2 slide-fwd-center">
    <div class="title"><b>🚀为什么选择Camel</b></div>
    <div class="content hvr-grow-shadow">
      <ol>
        <h3 style="margin-bottom: 10px">现代AI开发面临的困境：</h3>
        <li>
          <b>语义碎片化:</b>
          JIT追踪（例如TensorFlow）在代码意图和执行图之间产生了差距，迫使开发者进行调试和控制流程的妥协。
        </li>
        <li>
          <b>认知负荷:</b>
          特定框架的概念（梯度带，图阶段，分阶段执行）要求与ML理论正交的专业知识。
        </li>
        <li>
          <b>原型-部署鸿沟:</b>
          Python的动态性限制了深度优化，而静态语言则失去了高级ML抽象。
        </li>
      </ol>
      <ol>
        <h3 style="margin-bottom: 10px">Camel通过以下方式解决这些问题：</h3>
        <li>
          <b>一流的计算图:</b>
          原生图形原语取代了脆弱的追踪——代码直接定义了编译器优化的DAG。
        </li>
        <li>
          <b>阶段多态语义:</b>
          单一代码库可以交互执行（类Python的即时性）或编译成优化的二进制文件（具有C++级别的性能）。
        </li>
        <li>
          <b>类型驱动的自动化:</b>
          张量形状/类型在编译时静态指导内存规划、算子融合和并行化——零手动调整。
        </li>
      </ol>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
.indexView2 {
  display: flex;
  flex-wrap: wrap;
  margin-top: 80px;
}
.indexView2 .title {
  display: flex;
  height: 80px;
  width: 100%;
  font-size: 30px;
  border-radius: 10px;
  align-items: center;
  justify-content: center;
  background-color: #8bc6ec;
  background-image: linear-gradient(135deg, #8bc6ec 0%, #9599e2 100%);
}
.indexView2 .content {
  display: flex;

  flex-wrap: wrap;
  margin: 20px;
  margin-left: 200px;
  color: white;
}
.indexView2 .content li {
  margin-left: 40px;
  margin-bottom: 10px;
}

@keyframes slide-fwd-center {
  from {
    transform: translateX(20%); /* 动画开始时的位置 */
    opacity: 0; /* 动画开始时的透明度 */
  }
  to {
    transform: translateX(0); /* 动画结束时的位置 */
    opacity: 1; /* 动画结束时的透明度 */
  }
}
.slide-fwd-center {
  animation: slide-fwd-center 1s cubic-bezier(0.25, 0.46, 0.45, 0.94) both;
}
</style>
