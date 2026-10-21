---
title: Research
layout: research
permalink: /research
---

<style>
    .custom-list {
        font-size: 18px; 
    }
    .img {
        width: 100%; /* Make the image take up 100% of the container's width */
    }
    .div{
        max-width: 400px; /* Set a maximum width for the container on larger screens */
        margin-right: 10px;
        margin-top: 15px;
        float: left;
    }
</style>

We develop machine learning algorithms for robot learning and human-robot interaction. Our group is focusing on how robots acquire generalizable behaviors, collaborate naturally with humans, and continuously adapt to the physical world. We usually leverage generalizable priors from multimodal AI models to enable robots to learn, reason, and act robustly across diverse tasks and environments. 

##### 1. Robot Foundation Models (RFMs)

We focus on building robot foundation models that can generalize across diverse tasks and environments. Our current research is centered on Vision-Language-Action models (VLAs), a promising paradigm for general-purpose robot control. As VLAs rapidly advance, we are particularly interested in the following questions:

<strong>Are VLAs robust enough to be deployed in the real world?</strong> Strong benchmark performance may not always translate to reliable behavior under distribution shifts, such as novel objects, lighting changes, or perturbed instructions. We explore when and why VLAs fail, and how they can be made more reliable beyond controlled settings. Relevant publication: <a href="https://dill-vla.github.io/" target="_blank" rel="noopener noreferrer">DILL</a>
 
<strong>Are VLAs worth their size?</strong> Larger models often come with substantial computational cost and latency, which can be critical for real-time robot control. We investigate how model capacity relates to task performance, and explore more efficient designs that retain generalization with a smaller footprint. Relevant publication: <a href="https://openreview.net/pdf?id=hpx4c5nDsy" target="_blank" rel="noopener noreferrer">MicroVLA</a> 


##### 2. Human-Robot Interaction (HRI)

We are interested in how humans and robots can interact effectively and efficiently, with a particular focus on interaction as a means for robot learning. Our work is guided by the following directions:

<strong>What should an intuitive, effective, and efficient interface for robot learning look like?</strong> Robots learn from human input such as demonstrations, corrections, and feedback, yet the way this input is collected strongly affects both its quality and cost. We explore interfaces that lower the burden on human users while providing rich, useful signals for learning, so that people without robotics expertise can teach robots in practice. Relevant publication: <a href="https://clip-rt.github.io/" target="_blank" rel="noopener noreferrer">CLIP-RT</a>

<strong>How can humans and robots make decisions together through interaction?</strong> In many real-world settings, neither full human control nor full robot autonomy is ideal. We study shared autonomy, where a human and a robot jointly decide how to act, and investigate how the robot can infer human intent, assist when helpful, and adapt its level of autonomy to the situation. Relevant publication: <a href="https://arxiv.org/pdf/2309.07759" target="_blank" rel="noopener noreferrer">PROGrasp</a>


##### 3. Lifelong Robot Learning

We are interested in robots that keep learning throughout their lifetime, continually acquiring new skills while preserving what they have already learned. Yet when robots are adapted to new tasks or environments, they often lose earlier capabilities, a problem known as catastrophic forgetting.

<strong>How can robots avoid forgetting previously learned skills?</strong> We explore model architectures and learning mechanisms that allow robots to integrate new experiences over time while retaining prior knowledge. Relevant publication: <a href="https://arxiv.org/pdf/2610.24804" target="_blank" rel="noopener noreferrer">SARAM</a>

Our interests are not limited to these directions, and extend to any approach toward communicative, collaborative, and trustworthy robot software for the real world.

