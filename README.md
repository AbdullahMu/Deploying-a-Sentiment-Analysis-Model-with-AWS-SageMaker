<h1 id="project-deploying-a-sentiment-analysis-model-with-aws-sagemaker">Project: Deploying a Sentiment-Analysis Model with AWS SageMaker</h1>
<h2 id="setting-up-a-notebook-instance">Setting up a Notebook Instance</h2>
<p>The deployment project which you will be working on is intended to be done using Amazon’s SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.</p>
<p>If you have not yet done this, please see the beginning of Lesson 2 in which we walk through creating a notebook instance and cloning the deployment repository. Alternatively, you can follow the instructions below.</p>
<p>First, start by logging in to the  <a href="http://console.aws.amazon.com/">AWS console</a>, opening the SageMaker dashboard and clicking on  <strong>Create notebook instance</strong>.</p>
<p>You may choose any name you would like for your notebook. Also, using  <strong>ml.t2.medium</strong>  should be all that is necessary for the project. In addition, an  <strong>ml.t2.medium</strong>  instance is covered under the free tier.</p>
<p>Next, under  <strong>IAM role</strong>  select  <strong>Create a new role</strong>. You should get a pop-up window that looks like the one below. The only change that needs to be made is to select  <strong>None</strong>  under  <strong>S3 buckets you specify</strong>, as is shown in the image below.</p>
<p><img src="https://video.udacity-data.com/topher/2018/October/5bd74c8c_create-an-iam-role/create-an-iam-role.png" alt="Create an IAM role dialog box"></p>
<p>Once you have finished setting up the role for your notebook, your notebook instance settings should look something like the image below.</p>
<p><img src="https://video.udacity-data.com/topher/2018/October/5bd74cba_notebook-instance-settings/notebook-instance-settings.png" alt="Notebook instance settings"></p>
<p>Note that your notebook name may be different than the one displayed and the IAM role that appears will be different.</p>
<p>Next, scroll down to the section labelled  <strong>Git repositories</strong>. Here you will clone the  <code>https://github.com/udacity/sagemaker-deployment.git</code>  repository.</p>
<p>Once you have filled in all of the required values, the settings should look as so:</p>
<p><img src="https://video.udacity-data.com/topher/2019/February/5c59a95c_clone-git-repo-sagemaker/clone-git-repo-sagemaker.png" alt=""></p>
<p>You’re done! Click on  <strong>Create notebook instance</strong>.</p>
<p>Your notebook instance is now set up and ready to be used!</p>
<p>Once the Notebook instance has loaded, you will see a screen resembling the following.</p>
<p><img src="https://video.udacity-data.com/topher/2019/February/5c59aa8c_sagemaker-open-jupyter/sagemaker-open-jupyter.png" alt=""></p>
<h2 id="project-overview">Project Overview</h2>
<p>Welcome to the SageMaker deployment project! In this project you will construct a recurrent neural network for the purpose of determining the sentiment of a movie review using the IMDB data set. You will create this model using Amazon’s SageMaker service. In addition, you will deploy your model and construct a simple web app which will interact with the deployed model.</p>
<h2 id="project-instructions">Project Instructions</h2>
<p>The deployment project which you will be working on is intended to be done using Amazon’s SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.</p>
<h2 id="evaluation">Evaluation</h2>
<p>Your project will be reviewed by a Udacity reviewer against the deployment project  <a href="https://review.udacity.com/#!/rubrics/2262/view">rubric</a>. Review this rubric thoroughly, and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.</p>
<h2 id="project-submission">Project Submission</h2>
<p>When you are ready to submit your project, collect all of the files in the project directory and compress them into a single archive for upload. In particular, make sure that the following files are included:</p>
<ul>
<li>The  <code>SageMaker Project.ipynb</code>  file with fully functional code,  <strong>all code cells executed and displaying output</strong>, and  <strong>all questions answered</strong>.</li>
<li>An HTML or PDF export of the project notebook with the name  <code>report.html</code>  or  <code>report.pdf</code>.</li>
<li>The completed  <code>train/train.py</code>  and  <code>serve/predict.py</code>  python files.</li>
<li>The edited  <code>website/index.html</code>  file.<br>
You can access your notebook using the Action “Open Jupyter”.</li>
</ul>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

