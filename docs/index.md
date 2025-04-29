# AI Software Template Gitops

This repository contains the necessary content required for managing GitOps. It was created as part of an AI Software Template. The associated source component is available for reference in the **Overview** tab. You can find an example of this reference in the following image.

![Overview Tab](./images/overview-dependency.png)

# Deployed Resources
Based on the input from the AI Software Template, a deployment with the following characterisics was made:

# Model Server
**Model Server:** [vLLM]( https://github.com/rh-aiservices-bu/llm-on-openshift/tree/main/llm-servers/vllm/gpu)

**Port:** 8001

# Application
An application built from https://github.com/redhat-appstudio-mjf/rag2-apr29-1 will be stored in [quay.io/maysunfaisal/rag2-apr29-1](https://quay.io/maysunfaisal/rag2-apr29-1) and deployed through GitOps. This application is accessible on port **8501**.