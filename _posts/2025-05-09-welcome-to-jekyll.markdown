---
layout: default # Or your chosen theme's layout
title: Qinghe Liu - Academic CV
profile_image: /assets/images/profile_picture.jpg # Replace with your photo path
lang: en
---

<div class="resume-container academic-resume">

    <header class="resume-header">
        <div class="profile-intro">
            {% if page.profile_image %}
            <img src="{{ page.profile_image | relative_url }}" alt="Qinghe Liu" class="profile-picture">
            {% endif %}
            <div class="intro-text">
                <h1>QINGHE LIU</h1>
                <p class="tagline">Computer Science & Technology | Deep Learning | Point Cloud Processing</p>
                <div class="contact-info">
                    <p><i class="fas fa-phone"></i> +86 13280073386</p>
                    <p><i class="fas fa-envelope"></i> liuqinghe@nwafu.edu.cn</p>
                    {% if site.github_username %}
                    <p><i class="fab fa-github"></i> <a href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener noreferrer">{{ site.github_username }}</a></p>
                    {% endif %}
                    </div>
            </div>
        </div>
        <div class="summary">
            <h2><i class="fas fa-user-tie icon-gradient"></i>Profile</h2>
            <p>
                I am a recent graduate with a Bachelor's degree in Computer Science and Technology, deeply passionate about deep learning, point cloud processing, and computer vision. During my undergraduate studies, I focused on the segmentation of point clouds and images using deep learning techniques. I possess strong development skills in PyTorch, Python, C++, and CUDA C, and I am proficient in the Linux development environment. My academic performance has been consistently excellent (ranked 2nd out of 131 students), and I have been honored with the National Scholarship and the President's Scholarship. I have actively engaged in research projects, leading to a first-author publication in a SCI Q1 TOP journal. By optimizing classical point cloud neural networks, I have significantly improved model accuracy and operational efficiency, demonstrating strong research potential and practical abilities. I am currently seeking admission to a postgraduate program at your esteemed university to further my studies in related fields.
            </p>
        </div>
    </header>

    <section class="resume-section education">
        <h2><i class="fas fa-graduation-cap icon-gradient"></i>Education</h2>
        <div class="education-item">
            <h3>Northwest A&F University, China (Project 985 & Project 211 University)</h3>
            <p class="date-location">
                <span class="date">Sep 2020 - Jun 2024</span> |
                <span>B.Sc. in Computer Science and Technology</span>
            </p>
            <p><strong>Overall GPA:</strong> 90.58 / 100 (or 3.79 / 4.0, please adjust according to the HK university's scale if known)</p>
            <p><strong>Major Ranking:</strong> 2 / 131 (Top 1.5%)</p>
            <p><strong>English Proficiency:</strong> CET-4: 524, CET-6: 482 (If you have IELTS/TOEFL, please add here, e.g., IELTS: 7.0)</p>
            <p><strong>Core Courses:</strong> Advanced Mathematics, Computer Organization, Data Structures and Algorithms, Operating Systems, Computer Networks, Parallel Computing, Machine Learning, Computer Graphics, C Programming, Object-Oriented Programming (C++), Digital Logic and Digital Systems, Linear Algebra, Probability and Statistics, Database Theory and Applications.</p>
            <p><strong>Graduation Thesis:</strong> Comprehensive Analysis and Research on Point Cloud Grouping and Sampling Algorithms (<strong>Outstanding Undergraduate Thesis Award</strong>)
                <br><small>Addressing the high time complexity bottleneck of grouping and sampling algorithms in point cloud neural networks, this research designed a novel grid-based sampling and grouping scheme. Implemented efficiently using CUDA C, the optimized algorithm achieved a speedup of up to 35 times compared to current mainstream methods, effectively resolving the performance bottleneck.</small>
            </p>
        </div>
    </section>

    <section class="resume-section research">
        <h2><i class="fas fa-flask icon-gradient"></i>Research Output</h2>
        <div class="research-item publication">
            <h3><i class="fas fa-newspaper"></i>Publications</h3>
            <ul>
                <li>
                    <strong>Liu Q. (First Author)</strong>, Yang H.*, Wei J., Zhang Y., Yang S. (2024). <strong>FSDNET: A features spreading net with density for 3D segmentation in agriculture</strong>. <em>Computers and Electronics in Agriculture</em>, 222, 109073.
                    <br><span class="journal-details">(SCI, Q1, TOP Journal, IF: 8.3)</span>
                    <br><a href="https://doi.org/10.1016/j.compag.2024.109073" target="_blank" rel="noopener noreferrer">DOI: 10.1016/j.compag.2024.109073</a>
                </li>
                <li>
                    Yuan H., Zhang W., Yan T., <strong>Liu Q.</strong>, Wu Z., Yang H.*, Wei J. (2024). <strong>Point HorNet: Higher-Order Spatial Interaction Network for Point Clouds</strong>. In: <em>Proceedings of the 10th International Conference on Virtual Reality (ICVR 2024)</em>. Bournemouth, United Kingdom. pp. 240-248.
                    <br><span class="journal-details">(EI Indexed Conference)</span>
                    <br><a href="https://doi.org/10.1109/ICVR62393.2024.10868020" target="_blank" rel="noopener noreferrer">DOI: 10.1109/ICVR62393.2024.10868020</a>
                </li>
                <li>
                    <em>GPFEnet: a lightweight grid parallel feature extraction net for 3D segmentation in agriculture.</em>
                    <br><span class="journal-details">(Submitted to International Joint Conference on Neural Networks (IJCNN) - CCF C Conference, Under Review)</span>
                </li>
            </ul>
        </div>
        <div class="research-item software-copyright">
            <h3><i class="fas fa-copyright"></i>Software Copyrights</h3>
            <ul>
                <li>Fruit Recognition System Based on Point Cloud Density V1.0</li>
                <li>3D Fruit Tree Point Cloud Dataset Production System V1.0</li>
            </ul>
        </div>
    </section>

    <section class="resume-section projects">
        <h2><i class="fas fa-project-diagram icon-gradient"></i>Research & Project Experience</h2>
        <div class="project-item">
            <h3>Research on Lightweight Grid Parallel Feature Extraction Network for Point Clouds (GPFEnet) <span class="project-role">Lead Researcher & Developer</span></h3>
            <p class="date-location"><span class="date">Jun 2024 - Present (Expected)</span></p>
            <p>This project aims to further optimize the grid-based grouping and sampling algorithm developed in my undergraduate thesis, targeting a significant (35x) improvement in point cloud processing speed. By designing the lightweight GPFEnet, this research strives to enhance the efficiency and practicality of point cloud deep learning in real-world applications.</p>
            <p><strong>My Role:</strong> Core algorithm design and optimization, CUDA parallel implementation, network model construction, and experimental validation.</p>
        </div>
        <div class="project-item">
            <h3>Design of Point Cloud Neural Network based on Higher-Order Feature Interaction (Point HorNet) <span class="project-role">Core Project Member, Design & Implementation Lead</span></h3>
            <p class="date-location"><span class="date">Jun 2023 - Jun 2024</span></p>
            <p>Inspired by the HorNet model in image processing, this project introduced higher-order feature interaction concepts into point cloud deep learning, resulting in the Point HorNet architecture. Combined with attention mechanisms, the network focuses on improving semantic segmentation accuracy for point clouds. Achieved 73.7% mIoU in six-fold cross-validation on the S3DIS dataset, demonstrating its potential in complex scene understanding.</p>
            <p><strong>My Role:</strong> Contributed to network architecture design, implemented core modules (higher-order interaction and attention) in PyTorch, managed experimental data processing and analysis, and co-authored relevant sections of the publication.</p>
        </div>
        <div class="project-item">
            <h3>Research on 3D Fruit Phenotype Segmentation and Recognition using Point Cloud Deep Learning <span class="project-role">Principal Investigator, National Undergraduate Innovation and Entrepreneurship Training Program</span></h3>
            <p class="date-location"><span class="date">Jun 2022 - Jun 2024</span></p>
            <p>Addressing the challenge of precise fruit recognition in automated agricultural harvesting, this project involved creating a strawberry point cloud dataset in complex field environments using Multi-View Stereo (MVS) algorithms and depth cameras. By improving classical point cloud deep learning frameworks (e.g., PointNet++), we designed FSDNET, a novel density-based feature extraction and propagation network. FSDNET significantly enhanced fruit segmentation accuracy (mIoU improved by 1%-6%), providing key technical support for smart agriculture. Research findings were published in a SCI Q1 TOP journal.</p>
            <p><strong>My Role:</strong> Overall project lead, designed research methodology, constructed and annotated datasets, designed and implemented the FSDNET model in PyTorch, conducted experiments and performance optimization, wrote project reports, and led paper publication.</p>
        </div>
         <div class="project-item">
            <h3>Automated Fruit Recognition Based on 3D Point Clouds <span class="project-role">Core Participant, Provincial Undergraduate Innovation and Entrepreneurship Training Program</span></h3>
            <p class="date-location"><span class="date">Sep 2021 - Jun 2022</span></p>
            <p>This project was an initial exploration of applying 3D point cloud technology to agricultural fruit recognition. We created point cloud datasets for various fruits like apples and strawberries using MVS algorithms and applied classical deep learning frameworks such as PointNet++ and PAConv for segmentation and recognition tasks, laying the groundwork for subsequent in-depth research.</p>
            <p><strong>My Role:</strong> Participated in MVS algorithm implementation and dataset construction, point cloud preprocessing, training and testing of PointNet++ and other models, and experimental result analysis.</p>
        </div>
        <div class="project-item">
            <h3>Other Relevant Experience</h3>
             <ul>
                <li><strong>Neural Network Module Implementation:</strong> Developed fundamental neural network modules (fully connected layers, activation functions, loss functions, backpropagation) from scratch using C++. Successfully trained and tested on MNIST and house price prediction datasets, deepening understanding of underlying neural network principles.</li>
                <li><strong>MIPS CPU Design:</strong> Designed and implemented a five-stage pipelined MIPS CPU with branch prediction using Verilog HDL. Verified and tested on an FPGA development board, gaining familiarity with computer hardware design flow.</li>
                <li><strong>CUDA Parallel Computing Practice:</strong> Utilized CUDA C to parallelize key operators in point cloud grouping and sampling processes, significantly optimizing the speed of these operations in point cloud processing, demonstrating capabilities in parallel computing and performance optimization.</li>
            </ul>
        </div>
    </section>

    <section class="resume-section skills">
        <h2><i class="fas fa-cogs icon-gradient"></i>Technical Skills</h2>
        <ul class="skills-list">
            <li><strong>Programming Languages:</strong> Python (Proficient), C/C++ (Proficient), CUDA C (Proficient), MATLAB (Familiar)</li>
            <li><strong>Deep Learning Frameworks:</strong> PyTorch (Expert; capable of independently building, training, and debugging complex models)</li>
            <li><strong>Development Tools & Technologies:</strong> Linux/Ubuntu (Proficient with command line and development tools), Git version control, LaTeX (Scientific document preparation)</li>
            <li><strong>Point Cloud & Image Processing:</strong> MVS Algorithms (Proficient), Point Cloud Segmentation & Recognition, Feature Extraction & Propagation, Higher-Order Feature Interaction</li>
            <li><strong>Algorithms & Theoretical Foundations:</strong> Strong foundation in machine learning theory; proficient in classic algorithms including graph theory, number theory, dynamic programming, and greedy algorithms.</li>
            <li><strong>Experimental & Computational Environments:</strong> Familiar with configuring, experimenting, and efficiently running deep learning projects in multi-GPU/CPU environments.</li>
        </ul>
    </section>

    <section class="resume-section awards">
        <h2><i class="fas fa-award icon-gradient"></i>Awards & Honors</h2>
        <div class="awards-grid">
            <div class="award-item">
                <h4>Academic Awards & Honors</h4>
                <ul>
                    <li>President's Scholarship, Northwest A&F University (2022, one of the highest university-level honors)</li>
                    <li>National Scholarship (2021, National Level)</li>
                    <li>First-Class Academic Scholarship (2020, 2021, 2022, 2023, for four consecutive years)</li>
                    <li>Outstanding Undergraduate Thesis Award, College Level, Northwest A&F University (2024)</li>
                    <li>Outstanding University Student, Northwest A&F University (2021)</li>
                    <li>Outstanding Communist Youth League Member (2020)</li>
                </ul>
            </div>
            <div class="award-item">
                <h4>Competition Awards</h4>
                <ul>
                    <li>National Second Prize, China Robotics and Artificial Intelligence Competition - AI Innovation Track (2022, National Level)</li>
                    <li>First Prize (Provincial Level), China Robotics and Artificial Intelligence Competition - AI Innovation Track, Shaanxi (2022)</li>
                    <li>Third Prize (Provincial Level), China Robotics and Artificial Intelligence Competition - AI Innovation Track, Shaanxi (2023)</li>
                    <li>Second Prize (Provincial Level), Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM), Shaanxi (2021)</li>
                    <li>Second Prize (Provincial Level), China Collegiate Computer Design Competition, Shaanxi (2021, 2022)</li>
                    <li>Successful Participant (S-Prize), Mathematical Contest in Modeling (MCM/ICM) (2022, International)</li>
                    <li>National Finalist Award, China Collegiate Computer Design Competition (2022, National Level)</li>
                </ul>
            </div>
        </div>
    </section>
    # <section class="resume-section postgraduate-info">
    #     <h2><i class="fas fa-user-graduate icon-gradient"></i>Postgraduate Entrance Examination (Mainland China)</h2>
    #     <p><strong>Target Institution:</strong> Zhejiang University</p>
    #     <p><strong>Target Program:</strong> Electronic Information (Computer Technology)</p>
    #     <p><strong>Total Score (Preliminary Test):</strong> 349/500</p>
    #     <ul>
    #         <li>Politics: 64/100</li>
    #         <li>English I: 70/100</li>
    #         <li>Mathematics I: 105/150</li>
    #         <li>Computer Science Fundamentals (408): 110/150</li>
    #     </ul>
    # </section>

</div>
