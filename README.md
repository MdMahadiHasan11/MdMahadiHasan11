<img src="https://i.ibb.co/PtGXvhp/stock-vector-programming-web-banner-best-programming-languages-technology-process-of-software-develo.jpg" alt="Mokkapps GitHub README header image">
<p><a href=""><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height=25></a></p>


<h2>About Me</h2>
<p>
<p> <span className='lg:text-3xl text-xl font-bold'>Hi , I'm Md Mahadi Hasan</span> a passionate MERN stack developer with a strong foundation in modern web development technologies. My expertise lies in crafting scalable web applications using React.js, JavaScript (ES6+), and Tailwind CSS for sleek, responsive designs. With a solid grasp of HTML5 and CSS3, I ensure seamless integration of UI/UX principles into every project.</p>  
</p>
<p className='mt-4'> In backend development, I leverage the power of MongoDB for efficient data management and Firebase for real-time database capabilities. My server-side proficiency includes Node.js and Express.js, allowing me to build robust APIs and deliver optimal performance.</p>

<h2>Skills</h2>
<div style="box-shadow: 4px 4px 6px rgba(0, 255, 255, 0.7);" class="class="lg:grid md:grid lg:grid-cols-3 md:grid-cols-2 gap-8 px-10 py-5">
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>React</p>
        </div>
        <progress class="progress progress-success w-56" value="82" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>JavaScript</p>
        </div>
        <progress class="progress progress-success w-56" value="75" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>Tailwind</p>
        </div>
        <progress class="progress progress-success w-56" value="82" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>CSS3</p>
        </div>
        <progress class="progress progress-success w-56" value="75" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>HTML5</p>
        </div>
        <progress class="progress progress-success w-56" value="80" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>Firebase</p>
        </div>
        <progress class="progress progress-success w-56" value="70" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>MongoDB</p>
        </div>
        <progress class="progress progress-success w-56" value="75" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>Node.JS</p>
        </div>
        <progress class="progress progress-success w-56" value="65" max="100"></progress>
    </div>
    <div>
        <div class="flex justify-between font-bold w-56">
            <p>Express.JS</p>
        </div>
        <progress class="progress progress-success w-56" value="65" max="100"></progress>
    </div>
</div>

<h2 style="font-family: Arial, sans-serif; font-size: 24px; color: #333;">GitHub Commit Counts</h2>
    <div id="repos" style="font-family: Arial, sans-serif;">
        <!-- Example repositories -->
        <div class="repo" style="margin-bottom: 20px;">
            <p class="repo-name" style="font-weight: bold;">Repository 1: 
                <span class="commit-count" id="repo1-commits" style="color: green;">0</span> commits
            </p>
        </div>
        <div class="repo" style="margin-bottom: 20px;">
            <p class="repo-name" style="font-weight: bold;">Repository 2: 
                <span class="commit-count" id="repo2-commits" style="color: green;">0</span> commits
            </p>
        </div>
    </div>

    <script>
        async function fetchCommitCounts(repo, elementId) {
            const username = 'your-github-username';
            const repoName = repo;
            const response = await fetch(`https://api.github.com/repos/${username}/${repoName}/commits`);
            const commits = await response.json();
            document.getElementById(elementId).textContent = commits.length;
        }

        // Fetch commit counts for each repository
        fetchCommitCounts('repository1', 'repo1-commits');
        fetchCommitCounts('repository2', 'repo2-commits');
    </script>


