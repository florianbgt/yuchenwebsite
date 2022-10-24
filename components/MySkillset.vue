<template>
    <div>
        <h1 class="text-center">My Skillset</h1>
        <b-row class="mt-5">
            <b-col md=12 sm=6>
                <SkillItem level=5 label="Python">
                    <template>
                        <strong>My favorite programming language!</strong>
                    </template>
                </SkillItem>
            </b-col>
            <b-col sm=6>
                <SkillItem level=5 label="Statistics">
                    <template>
                        <strong>Deep interest in maths!</strong>
                        <br>
                        Regretion analysis | Programming in R
                    </template>
                </SkillItem>
            </b-col>
            <b-col sm=6>
                <SkillItem level=5 label="Data Analysis & Visualization">
                    <template>
                        NumPy | Pandas
                        <br>
                        Matplotlib | Seaborn | Tableau
                    </template>
                </SkillItem>
            </b-col>
            <b-col md=4 sm=6>
                <SkillItem level=5 label="Machine Learning & Deep Learning">
                    <template>
                        Sciki-learn | PyShark | MapReduce
                        <br>
                        Keras | Tensorflow
                    </template>
                </SkillItem>
            </b-col>
            <b-col md=4 class="d-none d-md-block">
                <Caroussel/>
            </b-col>
            <b-col md=4 sm=6>
                <SkillItem level=5 label="Databases">
                    <template>
                        PostgreSQL | MySQL | Neo4j
                    </template>
                </SkillItem>
            </b-col>
            <b-col sm=6>
                <SkillItem level=5 label="Physics">
                    <template>
                        Physics | Chemistry | Mechanics
                    </template>
                </SkillItem>
            </b-col>
            <b-col sm=6>
                <SkillItem level=3 label="Cloud solutions">
                    <template>
                        AWS RDS | AWS S3 | Firebase | GCP | Apache Kafka
                    </template>
                </SkillItem>
            </b-col>
            <b-col md=12 sm=6>
                <SkillItem level=2 label="REST API">
                    <strong>Currently learning about it!</strong>
                    <br>
                    <template>
                        Django | Django REST
                    </template>
                </SkillItem>
            </b-col>
        </b-row>
    </div>
</template>