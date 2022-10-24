<template>
  <b-container class="py-5" style="max-width: 600px">
    <h1 class="text-center">My Timeline</h1>
    <TimelineItem
      :title="{
        icon: ['fas', 'graduation-cap'],
        value: 'Msc in Data Science'
      }"
      date="Dec 2021"
      :place="{
        icon: ['fas', 'university'],
        value: 'Brown University'
      }"
      location="Providence, RI, USA"
    >
      <div class="mt-3">
      <strong
        >Graduate in december 2021 (current GPA of 3.8/4)</strong
      >
      </div>
    </TimelineItem>
    <div class="my-5"></div>
    <TimelineItem
      :title="{ icon: ['fas', 'user'], value: 'AI/ML research intern' }"
      date="Jul 2021 to Oct 2021"
      :place="{ icon: ['fas', 'briefcase'], value: 'Softinway' }"
      location="Boston, MA, USA"
    >
      <div class="mt-3">
      <strong>
        Axial compressor performance prediction using AI & ML techniques
      </strong>
      </div>
      <ul class="pl-3">
        <li>
          Use AutoKeras to build deep learning models to predict axial compressor performance, with metrics efficiencies and pressure rate.
          Automatically find the best model architecture and hyperparameters accordingly given different compressor features as input results in prediction efficiencies and pressure rate error (RMSE) around 1e-5.
        </li>
        <li>
          Use Gaussian Mixture models (GMM) to generate a synthetic dataset that has similar statistical distribution with the current dataset to improve models’ performance on a small dataset.
          Result in RMSE improves from 1e-4 to 1e-5 by adding the synthetic data.
        </li>
        <li>
          Deliver a ready-to-use model for automating turbomachinery design that enables people with limited machine learning backgrounds to use the models easily, saving the cost of design and smoothing the collaboration between the AI research team and the engineering team.
          Deliver reports, visualize results, and explain to non-machine learning background audiences and other collaborative teams.
        </li>
      </ul>
    </TimelineItem>
    <div class="my-5"></div>
    <TimelineItem
      :title="{ icon: ['fas', 'user'], value: 'Research assistant' }"
      date="June 2021 to current"
      :place="{ icon: ['fas', 'briefcase'], value: 'Brown University' }"
      location="Providence, RI, USA"
    >
      <div class="mt-3">
      <strong>
        Predict Patient Anxiety Using Machine Learning during Radiation Cancer Treatment
      </strong>
      </div>
      <ul class="pl-3">
        <li>
          Use Python, R, and MATLAB to preprocess physiological responses data acquired from wearable sensors of patients, perform feature engineering to get valuable features.
          Check correlation using Pearson correlation between skin conductance and acceleration data to investigate if motion affects skin conductance data and denoise the data accordingly.
        </li>
        <li>
          Use Python to implement machine learning models, including unsupervised learning and supervised learning models.
          Cluster segments data into different categories and compares them with tagged events during the CT (cancer treatment) sessions, providing insightful information and evaluating the marking method.
        </li>
        <li>
          Build classification models use Logistic regression, XGBoost, Random Forest algorithms to detect whether patients have anxiety during their CT sessions.
          Visualize and analyze the prediction results and give insightful information on how to help better plan for more efficient and safe radiation therapy treatment.
        </li>
      </ul>
    </TimelineItem>
    <div class="my-5"></div>
    <TimelineItem
      :title="{ icon: ['fas', 'user'], value: 'Teaching assistant' }"
      date="Jan 2021 to May 2021"
      :place="{ icon: ['fas', 'briefcase'], value: 'Brown University' }"
      location="Providence, RI, USA"
    >
      <ul class="pl-3 mt-3">
        <li>
          Assist design statistical testing procedure, including using multiple hypothesis tests such FWER (Family-wise error-rate) control to analyze real-world clinic trial data, aims to explore if the newly developed drug alleviates cancer disease symptoms by comparing between control and experiment group
        </li>
        <li>
          Assist in designing and implementing MapReduce algorithms equivalent with mappers and reducers in Spark usingPySpark from Python. Apply the MapReduce framework to the movie recommendation system.
        </li>
        <li>
          Assist design and implement topic modeling/latent semantic analysis (LSA) using tf-idf scores in natural language processing (NLP), implement classification (KNN) and clustering (k-means) algorithms to category documents.
        </li>
      </ul>
    </TimelineItem>
    <div class="my-5"></div>
    <TimelineItem
      :title="{
        icon: ['fas', 'graduation-cap'],
        value: 'Msc in Physics'
      }"
      date="Aug 2018 - May 2020"
      :place="{
        icon: ['fas', 'university'],
        value: 'Brown University'
      }"
      location="Providence, RI, USA"
    >
    </TimelineItem>
    <div class="my-5"></div>
    <TimelineItem
      :title="{
        icon: ['fas', 'graduation-cap'],
        value: 'Bsc in Applied Physics'
      }"
      date="Aug 2014 - Jun 2018"
      :place="{
        icon: ['fas', 'university'],
        value: 'East China University of Science and Technology'
      }"
      location="Shanghai, China"
    >
      <div class="mt-3">
      <strong>GPA of 3.5/4</strong
      >
      </div>
    </TimelineItem>
  </b-container>
</template>
