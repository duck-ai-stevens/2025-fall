---
layout: home
---

<script>
function toggleContent(button) {
    const content = button.previousElementSibling;
    content.classList.toggle('collapsed');
    if (content.classList.contains('collapsed')) {
        button.textContent = 'More';
    } else {
        button.textContent = 'Less';
    }
}
</script>

<!-- Add this CSS to control appearance -->
<style>
.expandable-content {
    max-height: 7em; /* Adjust how much you want to initially show */
    overflow: hidden;
    position: relative;
    transition: max-height 0.3s ease;
}

.expandable-content.collapsed {
    max-height: 3.2em;
}

.expandable-content:not(.collapsed) {
    max-height: 1000em; /* Expand fully */
}

.expand-btn {
    margin-top: 0.5em;
    padding: 0.4em 0.8em;
    font-size: 0.9em;
    background-color: #eee;
    border: 1px solid #ccc;
    cursor: pointer;
    border-radius: 5px;
}
</style>

<!-- ![topic_banner](/_images/banner.jpg) -->

Following the strong momentum and community engagement demonstrated during [DuckAI 2025 Spring](https://duck-ai-stevens.github.io/2025-spring/), the 2nd iCNS/ECE Symposium on AI Research and Innovations (DuckAI 2025 Fall), scheduled on **December 10th 2025**, continues to expand our research and educational mission. The invited talks will be held in **Howe 409 (Bissinger)**, and the poster session will take place in **Library B12**.

This one-day event is organized by the [Center for Innovative Computing and Networked Systems (iCNS)](https://www.stevens.edu/icns-center-for-innovative-computing-and-networked-systems) and the [Department of Electrical and Computer Engineering](https://www.stevens.edu/school-engineering-science/departments/electrical-computer-engineering) at Stevens. It aims to bring together industry partners, researchers, faculty, and students to discuss recent developments in AI techniques and applications. The symposium features two technical sessions with invited talks, along with a poster & demo session where around 30 student teams will showcase their AI projects for Fall’25.

<!-- 

<!-- <div style="background: linear-gradient(135deg, #ff6b6b, #ffa500); 
            color: white; 
            padding: 15px 20px; 
            border-radius: 8px; 
            margin-bottom: 20px; 
            text-align: center;
            font-family: Arial, sans-serif;">

  <p style="margin: 0 0 8px; font-size: 16px; line-height: 1.5;">
    If you are unable to attend in person, you can join the meeting online via Zoom:
  </p>

  <a href="https://stevens.zoom.us/s/95279443855"
     style="display: inline-block; 
            margin-top: 4px; 
            font-size: 16px; 
            font-weight: bold; 
            text-decoration: underline; 
            color: #ffffff;">
    Join Zoom Meeting
  </a>

</div>


<!-- ## Event Agenda

- Schedule on **Wednesday, December 10, 2025**
- 9:00 a.m. – 4:00 p.m.
- Morning session (talk session): **Howe 409 (Bissinger)**
- Afternoon session (poster session): **Library B-12** -->

<!--

## Agenda

- 9:00 AM - Check in
- 9:15 AM - Opening Remarks by ECE Department Chair: Dr. Min Song
- 9:30 AM - Invited Talk Session 1 - Host: Dr. Hao Wang
- 10:20 AM - Coffee Break
- 10:40 AM - Invited Talk Session 2 - Host: Dr. Shucheng Yu
- 11:30 AM - Lunch
- 1:00 PM - Student Project Poster & Demo
- 2:30 PM - Award announcement
- 3:00 PM - Adjourn -->

<!-- Registration link: [https://forms.gle/2A2kscme9qP74CBHA](https://forms.gle/2A2kscme9qP74CBHA)

<!--You can also register by scanning the QR code:

<img src="_images/qr-code.svg" alt="QR code" style="width: 200px; max-width: 100%; display: block; margin: 1em 0;" /> -->

## Invited Speakers

<div class="home" style="font-size: 1em;">
    <ul class="responsive-table" style="margin-left: 0; border-bottom: 0.1em solid whitesmoke;">
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/TianhaoWu.png" class="image--cover">
                </div>
                <div class="image--cover-container">
                    <img src="_images/YingchaoZhang.png" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b>Tianhao Wu and Yingchao Zhang</b> | opAIda, Inc.</p>
                <b>Open-Source AI: Data All-in-One</b>
                <div class="expandable-content collapsed">
                    <p>In this talk, Dr. Tianhao Wu, founder and CEO of opAIda, presents a practical and scalable strategy for unlocking business ROI through a Data All-in-One architecture powered by open-source AI. The approach emphasizes affordability, data ownership, and operational control by combining open-source LLMs with low-cost, high-performance hardware.</p>
                    <p>Dr. Wu introduces the Unified Data Agent (UDA)—a customizable AI agent designed to eliminate the pervasive challenge of enterprise data silos. UDA unifies disconnected data sources such as email, chat, cloud drives, and databases without requiring any manual work. By learning directly from real human actions and institutional processes, the system automates complex workflows including RFI responses, event operations, task prioritization and cross-team coordination. The result is a continuously improving AI ecosystem where organizational knowledge is preserved, searchable, and actionable through semantic retrieval. This Data All-in-One framework demonstrates how open-source AI can deliver immediate efficiency gains while laying the foundation for long-term digital transformation.</p>
                    <p><b>Short Bio:</b> Dr. Tianhao Wu is a trailblazer in artificial intelligence and a visionary leader with over 24 years of experience transforming complex business challenges into scalable AI solutions. Before co-founding opAida.ai, he founded AYR, Inc., where he pioneered the Singularity AI platform. In 2023, following a rigorous two-year evaluation of more than 50 vendors—including Microsoft and Google—his AI technology was selected exclusively by the U.S. Internal Revenue Service to automate all paper-filed tax returns nationwide. A hands-on innovator, Dr. Wu has delivered over 200 machine learning use cases across government and highly regulated industries, with solutions powering platforms for the U.S. National Institute of Justice, Lockheed Martin, and WorkFusion. He holds a Ph.D. in Machine Learning from Lehigh University and a B.Eng. in Computer Science from Peking University, with four granted patents and three pending. His early work building AI-powered search technology at Ask.com further solidifies his reputation as a pioneering force in enterprise AI.</p>
                    <p>Dr. Yingchao Zhang, widely known as “Dr. YZ,” is a highly respected technology executive with over two decades of experience spanning system administration, cybersecurity, software engineering, and AI innovation. A nuclear physicist by training, he made a bold pivot into tech in 1997 and has since led transformative initiatives across startups, research institutions, and enterprise environments—including key roles at NetScout serving Fortune 500 clients. He holds a Ph.D. in Nuclear Physics from Stony Brook University and a B.Sc. from the University of Science and Technology of China. In recognition of his leadership, Dr. YZ was named one of the Outstanding 50 Asian Americans in Business in 2023 and appointed in 2025 by New Jersey Governor Phil Murphy to the Board of Trustees of Thomas Edison State University. At opAida.ai, he brings strategic vision, deep technical expertise, and operational excellence to the company’s mission of delivering secure, scalable AI solutions.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>
        </li>
                <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/MingyuDerekMa.jpg" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="https://derek.ma/">Mingyu Derek Ma</a></b> | Prescient Design, Genentech </p>
                <b>Elevating Large Language Models to Expert Intelligence</b>
                <div class="expandable-content collapsed">
                    <p>Large Language Models (LLMs) have been applied to expert domains and scientific contexts, such as clinical diagnosis and drug discovery. However, the generalizability that characterizes LLMs in the general domain does not readily translate to scientific and expert tasks. Unlike general natural language tasks, scientific data is densely packed, homogeneous, and less self-explanatory. Moreover, expert-level tasks, such as those performed by physicians, engineers, or scientists, require deep domain knowledge, intuitive reasoning, and multi-step planning, refined through years of specialized training. In this talk, I will first discuss capturing implicit expert intuition for individual decision-making, using clinical diagnosis prediction as a case study. I will then extend the focus to compositional, project-level reasoning and automation, highlighting the development of LLM agents for scientific discovery.</p>
                    <p><b>Short Bio:</b> Mingyu Derek Ma is a Senior Machine Learning Scientist at Prescient Design, Genentech (Roche), where he leads the development of agentic intelligence and automation platforms for drug discovery and contributes to training scientific large language models. His work focuses on the architecture, training, and agentic use of generative language models inspired by and applied to clinical, medical, and scientific scenarios. His research has been recognized as one of the top 15 most-cited papers at NAACL 2024 and has been published at leading AI conferences like ACL, AAAI, and NeurIPS. He obtained his PhD in Computer Science from UCLA and received the J.P. Morgan Chase AI PhD Fellowship and Amazon Fellowship.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>
        </li>
        <li class="table-row">
            <div class="col-12 col-md-12">
                <div class="image--cover-container">
                    <img src="_images/YulongCao.jpg" class="image--cover">
                </div>
            </div>
            <div class="col-12 col-md-12">
                <p><b><a href="https://research.nvidia.com/person/yulong-cao">Yulong Cao</a></b> | Autonomous Driving, NVIDIA </p>
                <b>Towards Safe and Human-aligned Autonomous Driving</b>
                <div class="expandable-content collapsed">
                    <p>Ensuring the security and safety of autonomous driving systems is a critical challenge due to the inherent safety risks. Building safe and human-aligned autonomous driving systems in real-world scenarios remains unresolved due to the complex and varied nature of driving behaviors and semantics. In this talk, I will present recent research efforts aimed at rethinking the testing of AV systems. The discussion will focus on two key areas: 1) modeling diverse behaviors using advanced traffic models, and 2) leveraging foundation models to enhance simulation capabilities and accelerate the testing process.</p>
                    <p><b>Short Bio:</b> Yulong Cao is a research scientist at the NVIDIA Autonomous Vehicle Research group directed by Marco Pavone. His research interest is in the intersection of security, privacy, and machine learning. His research goal is to build trustworthy machine learning systems that are aligned with human in the real world, with a focus on autonomous driving systems. He completed his Ph.D from the Computer Science and Engineering department of University of Michigan, advised by Morley Mao. and holds B.S. degrees from University of Michigan and Shanghai Jiao Tong University.</p>
                </div>
                <button class="expand-btn" onclick="toggleContent(this)">More</button>
            </div>
        </li>
    </ul>
</div>

## Organizers:

- [Hao Wang](https://intellisys.haow.us/haowang/)
- [Joseph Helsing](https://www.stevens.edu/profile/jhelsing)
- [Min Song](https://www.stevens.edu/profile/msong6)
- Jessica Gruich
- [Kevin Lu](https://www.stevens.edu/profile/klu2)

## Volunteers:

- [Rui Wei](https://me.waynetech.site/)
- Qingyang Yu
- Hao (Lucas) Wang
- Xuan Li

<!-- ## Special Thanks -->

<!--
**Important Dates:**
* ~~Submission deadline: April 1, 2025~~
* ~~Acceptance notification: April 15, 2025~~
* Final version: May 30, 2025
* PER Camera ready: June 30, 2025
* Workshop date: June 13, 2025 -->

## Moments at DuckAI 2025 Fall
<div class="profile-pic-gallary">
    <h2>Moments from the event</h2>
    <div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_7134.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_7183.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_7460.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_7584.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_7822.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8211.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8277.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8668.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8693.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8895.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8920.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_8986.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_9061.jpeg" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_9094.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_9108.JPG" class="image--cover">
        </div>
        <div class="image--cover-container">
            <img src="/_images/photos/DSC_9131.JPG" class="image--cover">
        </div>
    </div>
</div>

More photos can be found [here](https://stevens0-my.sharepoint.com/:f:/g/personal/rwei7_stevens_edu/IgAr-c2O2JX2TZXyMlm_ZPd2AUkDZUhaSVO7oYZoXtQjRyw?e=Znl9Rb)