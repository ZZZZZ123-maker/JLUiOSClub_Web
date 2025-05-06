---
title: MAIC 官方宣讲会
description: 移动应用赛官方宣讲会
---

# 移动应用创新赛——官方宣讲会来啦！

> 🗓️ 日期：2025年**05月11日**
>
> 🕜 时间：晚 19:00
>
> 🏢 地点：南区计算机楼 B110
>
> 👩🏻‍💻 主讲人：吉林大学MAIC的指导教师谷方明
> 
> ✋ 竞赛官网：[竞赛官网](https://www.appcontext.net)

## 活动亮点

![活动海报](poster.jpg)

“移动应用创新赛”是 “中国高校计算机大赛” 所设立的四个竞赛模块之一，是由 Apple 与浙江大学联合举办、面向高校学员、供应链员工、K12 组别学生推出的基于 iOS/iPadOS 平台设计开发应用的竞赛。

为了更好地组织推广移动应用创新赛，JLUiOSClub安排了一场宣讲会，选址在吉林大学前卫南区。

## 竞赛亮点

- **Apple 中国官方支持**，连续多年入选全国普通高校大学生竞赛排行榜
- 获奖作品有机会直通“互联网+”、大创等创新创意赛，推荐进入**全国总决赛**
- 2022年起列入吉林大学 **B* 类竞赛**，享有加分和推免等政策
- 参赛全程**完全免费**，奖励丰厚

## 活动流程

<el-timeline style="max-width: 600px">
  <el-timeline-item
    v-for="(step, index) in steps"
    :key="index"
    :timestamp="step.time"
    type="primary"
  >
    <span style="font-weight: bold;margin: 0;">{{ step.name }}</span>
    <br></br>主讲人：{{ step.people }}
  </el-timeline-item>
</el-timeline>

## 🔥 加入2024-MAIC竞赛群

![点击图片可放大](/competitions/maic/maic-qr.jpg)

## 关注 JLU iOS Club

<dualQRCode/>

<script setup>
import {ElTimeline, ElTimelineItem, ElButton} from 'element-plus';
import { useRouter } from 'vitepress';
import dualQRCode from '/components/dualQRCode.vue';

const steps = [
  {
    name: "活动开场",
    people: "JLU iOS Club",
    time: "13:30"
  },
  {
    name: "移动应用创新赛宣讲",
    people: "上海交通大学 董占勋",
    time: "13:30～14:40"
  },
  {
    name: "互动答疑+合影",
    people: "组委会秘书 曹颖萍",
    time: "14:40～15:00"
  },
];
const router = useRouter();
</script>

<style scoped>
ul.el-timeline {
    list-style: none;
}
</style>
