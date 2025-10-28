---
title: "Experience"
date: 2025-10-28T12:00:00-07:00
draft: false
---

<style>
.experience-timeline {
  position: relative;
  margin: 2.5rem 0 2.5rem 0;
  padding-left: 44px;
  max-width: 900px;
}
.experience-timeline::before {
  content: "";
  position: absolute;
  left: 24px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: #fff2;
}
.timeline-entry {
  display: flex;
  align-items: flex-start;
  margin-bottom: 3.2rem;
  position: relative;
}
.timeline-dot {
  position: absolute;
  top: 8px;
  left: -27px;
  width: 16px;
  height: 16px;
  background: #fff;
  border-radius: 50%;
  border: 2px solid #fff2;
  z-index: 1;
}

.timeline-left {
  flex: 0 0 180px;
  text-align: right;
  padding-right: 32px;
  font-size: 1.05rem;
  color: #fff;
}
.timeline-company {
  font-weight: bold;
  font-size: 1.08rem;
}
.timeline-dates {
  font-size: 0.98rem;
  color: #fff9;
}
.timeline-role {
  font-style: italic;
  font-size: 0.97rem;
  color: #fff9;
}
.timeline-right {
  flex: 1 1 0;
  padding-left: 8px;
  color: #fff;
}
.timeline-title {
  font-weight: bold;
  font-size: 1.08rem;
  font-style: italic;
  margin-bottom: 0.2rem;
}
.timeline-desc {
  font-size: 1.01rem;
  line-height: 1.6;
  margin-bottom: 0.6rem;
}
.timeline-readmore {
  display: inline-block;
  margin-top: 0.5rem;
  padding: 0.3em 1em;
  background: #fff1;
  border-radius: 18px;
  color: #fff;
  font-size: 0.97rem;
  border: none;
  cursor: pointer;
}
@media (max-width: 700px) {
  .experience-timeline {
    padding-left: 0;
  }
  .timeline-entry {
    flex-direction: column;
    padding-left: 36px;
  }
  .timeline-left {
    text-align: left;
    padding-right: 0;
    margin-bottom: 0.5rem;
  }
  .timeline-right {
    padding-left: 0;
  }
}
</style>

<div class="experience-timeline">

  <div class="timeline-entry">
    <div class="timeline-dot"></div>
    <div class="timeline-left">
      <div class="timeline-company">Square</div>
      <div class="timeline-dates">June, 2025 – Sept, 2025</div>
      <div class="timeline-role">SWE Intern</div>
    </div>
    <div class="timeline-right">
      <div class="timeline-title">Proxy Service & Efficiency</div>
      <div class="timeline-desc">At Square I was tasked with implementing a micro-service for Square's merchant email service. It served as a proxy which would subsequently fan out asynchronous requests to 4 other microservices in order to aggregate data. I implemented Redis Caching for Week over Week and Year over Year comparison data which addressed a bottleneck in latency during peak hours in which the email was triggered to send.</div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="timeline-dot"></div>
    <div class="timeline-left">
      <div class="timeline-company">Dexcom</div>
      <div class="timeline-dates">Jun, 2024 – Aug, 2024</div>
      <div class="timeline-role">SWE Intern</div>
    </div>
    <div class="timeline-right">
      <div class="timeline-title">Helping Devs Find Answers Faster</div>
      <div class="timeline-desc">At Dexcom, my goal was to create a full stack Rest API in order to automate the validation of partner application tokens in order for Dexcom Partner devs to troubleshoot buggy applications quicker. I designed the frontend with Angular and the backend was implemented in Kotlin and Springboot and the data layer included GCP datastore.</div>
    </div>
  </div>

  <div class="timeline-entry">
    <div class="timeline-dot"></div>
    <div class="timeline-left">
      <div class="timeline-company">Argonne National Lab</div>
      <div class="timeline-dates">Jun, 2023 – Aug, 2023</div>
      <div class="timeline-role">SWE Research Intern</div>
    </div>
    <div class="timeline-right">
      <div class="timeline-title">Image Regression Research</div>
      <div class="timeline-desc">My internship with Argonne was the first professional experience that I had. As a freshman, I took it upon myself to learn the underlying logic behind concepts like convolutional neural networks, fine tuning parameters, and minimizing loss. I developed an image classification model as a proof of concept and consequently implemented and deployed the regression model into Argonne's Waggle Nodes in order to identify solar irradiance levels based on images of the sky.</div>
    </div>
  </div>


</div>
