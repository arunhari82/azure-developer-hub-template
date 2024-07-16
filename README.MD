# Developer Hub Template for Spring boot app + Azure Devops (CI) + Argo (CD) + Service Mesh

This repository contains the Backstage Template used to create the Kubernetes resources needed to build/deploy a simple Spring Boot application and configures Azure Pipelines (CI) , Argo (Gitops) and also deploys ServiceMesh resources

## Introduction 
This template has been designed to work only with TAP demo (https://demo.redhat.com/catalog?item=babylon-catalog-prod/enterprise.redhat-tap-demo.prod&utm_source=webapp&utm_medium=share-link) it assumes all the infrastructure required are available.

## Registering Template.

This new template can be registered on developer hub instance with Register existing component from create section. The URL should be (https://github.com/arunhari82/azure-developer-hub-template/blob/main/templates/github/spring-boot-backend/template.yaml)

## Azure Requirement :

  1) Azure devops Account and Org
  2) Create a Azure Project with name : "Developer Hub Demo"
  3) Personal Access Token with following 
       ``` 
            Build - Read and Execute
            Code - Full
            Packaging - Read ,Write, & Manage
            Pipeline Resources - Use and Manage
            Pull Request Threads - Read & write
            Release - Read
        ```