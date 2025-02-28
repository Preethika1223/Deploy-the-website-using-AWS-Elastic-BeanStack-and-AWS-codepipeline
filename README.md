# AWS Elastic Beanstalk and CodePipeline Integration

This project demonstrates how to deploy a web application using AWS Elastic Beanstalk and automate the deployment process using AWS CodePipeline.

## Steps to Reproduce

1. **Elastic Beanstalk Setup**:
   - Created an Elastic Beanstalk application and environment.
   - Configured the environment to use a single instance with a spot instance.
   - Set up the root volume as GENERAL PURPOSE 3 (SSD).
   - Deployed the default website and verified its functionality.

2. **CodePipeline Setup**:
   - Created a pipeline to automate deployments from a GitHub repository.
   - Connected the pipeline to the GitHub repository.
   - Configured the pipeline to deploy changes to the Elastic Beanstalk environment.

3. **Testing the Pipeline**:
   - Made changes to the `index.html` file in the GitHub repository.
   - Verified that the pipeline automatically deployed the changes to the Elastic Beanstalk environment.


## Conclusion

This setup demonstrates the power of AWS Elastic Beanstalk and CodePipeline in automating web application deployments. By integrating GitHub as the source, changes can be deployed seamlessly to the live environment.
