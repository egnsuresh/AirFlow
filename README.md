# AirFlow
all about AirFlow

AirFlow written In Python and it is Apache Open Source Project

#Before AirFlow

Cron jobs

limitations with cron jobs
1. Error handling (handiling of error while running jobs, what to do, what not to do, like restart of same job and how many times need to retry)
2. Tracebility (what changed, when .. ect)
3. Dependent Executions (do task B after task A, since B is dependent on A)
4. Transparancy (logging each stage and storing in common place)
5. Tracking Jobs (when started, succeeded, failed, why failed)
6. Processing Historic data (to process the data which is produced in few months.. etc)

#How AirFlow will work
we can use DAG work flow (Directed Acyclic Graph)
Pipelines are configurable using Pyton programming to achieve dynamic configurations as when required
Extension of AirFlow is possible using custom defined operators and executors 
Scalable as moduler for each task
Configurable using airflow.cfg along with DAG (editing of DAG also airflow.cfg file

UI to monitor the DAG in AirFlow
Centralized Configuration
Customised retry for dependent jobs to execute next jobs
Email triggers

#Who is using 
Airbnb, Spotify, Stripe

Migration to AirFlow currently trending

#Terminology
DAG= Directed Acylic Graph (undirectional, conneting edges, each Node is task, edges will be dependencies)
Operator= Single Task in DAG work flow
Task= done by workers once it got instantiated, task (when it is instantiaded) = Operator
Workflow= sequence of tasks, it is interchangeably with DAG





