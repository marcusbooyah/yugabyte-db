---
title: Amazon Web Services
linkTitle: Amazon Web Services
description: Amazon Web Services
block_indexing: true
menu:
  v1.2:
    identifier: deploy-in-aws
    parent: public-clouds
    weight: 630
---

<ul class="nav nav-tabs nav-tabs-yb">
  <li>
    <a href="#cloudformation" class="nav-link active" id="cloudformation-tab" data-toggle="tab" role="tab" aria-controls="cloudformation" aria-selected="true">
      <i class="icon-shell"></i>
      CloudFormation
    </a>
  </li>
  <li>
    <a href="#terraform" class="nav-link" id="terraform-tab" data-toggle="tab" role="tab" aria-controls="terraform" aria-selected="true">
      <i class="icon-shell"></i>
      Terraform
    </a>
  </li>
  <li>
    <a href="#manual-deployment" class="nav-link" id="manual-deployment-tab" data-toggle="tab" role="tab" aria-controls="manual-deployment" aria-selected="true">
      <i class="icon-shell"></i>
      Manual Deployment
    </a>
  </li>
</ul>

<div class="tab-content">
  <div id="cloudformation" class="tab-pane fade show active" role="tabpanel" aria-labelledby="cloudformation-tab">
    {{% includeMarkdown "aws/cloudformation.md" /%}}
  </div>
  <div id="terraform" class="tab-pane fade" role="tabpanel" aria-labelledby="terraform-tab">
    {{% includeMarkdown "aws/terraform.md" /%}}
  </div>
   <div id="manual-deployment" class="tab-pane fade" role="tabpanel" aria-labelledby="manual-deployment-tab">
    {{% includeMarkdown "aws/manual-deployment.md" /%}}
  </div>
</div>
