---
layout: post
title:  "Eclipse Web project로의 여정"
date:   2017-11-13 00:20:59
author: Jerry Ahn
categories: Web Programming
tags:	Eclipse, Java, Web
cover:  "/assets/instacode.png"

---

# Eclipse Web project로의 여정

#### 1) 동기

많은 분들이 처음 Java를 학습 할 때, 이클립스 IDE를 설치하고 예시를 따라서 기본프로젝트로 src 하단에 `Helloworld.java`  를 작성한 경험이 있을것으로 생각합니다.

기본프로젝트 이후로, Servlet, Spring 등 웹 프로젝트를 학습하면서 조금 더 복잡한 프로젝트 구조를 만나게 됩니다.

<a href="//doublems.github.io/assets/postphoto/20171112_1.PNG" data-lightbox="웹프로젝트 시작" data-title="웹프로젝트 시작">
  <img src="//doublems.github.io/assets/postphoto/20171112_1.PNG" title="웹프로젝트 시작">
</a>

책이나 예시 자료등을 보고 따라하는 웹프로젝트의 첫 학습은 흔히 기본프로젝트와는 별개로 새로운 프로젝트로 시작됩니다. (제 경험에 의하면) 기존에 학습하던 프로젝트 방식과 맥락이 이어지지 않는 갑작스런 변화는 프로젝트가 복잡하고 어렵다고 생각하게 합니다.

평소, 프로젝트 구조도 궁금하기도 했고, 어떻게 하면 프로젝트가 확장되어 진행 될 수 있는지 궁금하여 본 글을 작성하게 되었습니다. 

따라서  이 글은 **기본프로젝트  `HelloWolrd.java` 부터 웹프로젝트까지의 프로젝트의 연결이 궁금하신 분** 들에게 도움이 될 수 있을 것으로 생각됩니다.