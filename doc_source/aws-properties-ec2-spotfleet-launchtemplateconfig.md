# Amazon Elastic Compute Cloud SpotFleet LaunchTemplateConfig<a name="aws-properties-ec2-spotfleet-launchtemplateconfig"></a>

`LaunchTemplateConfig` is a property of the [Amazon EC2 SpotFleet SpotFleetRequestConfigData](aws-properties-ec2-spotfleet-spotfleetrequestconfigdata.md) property that describes a launch template and overrides\.

## Syntax<a name="w2922ab1c21c10c96d122c45b5"></a>

### JSON<a name="aws-properties-ec2-spotfleet-launchtemplateconfig-syntax.json"></a>

```
{
  "[LaunchTemplateSpecification](#cfn-ec2-spotfleet-launchtemplateconfig-launchtemplatespecification)" : [*LaunchTemplateSpecification*](aws-properties-ec2-spotfleet-fleetlaunchtemplatespecification.md),
  "[Overrides](#cfn-ec2-spotfleet-launchtemplateconfig-overrides)" : [ [*LaunchTemplateOverrides*](aws-properties-ec2-spotfleet-launchtemplateoverrides.md), ... ]
}
```

### YAML<a name="aws-properties-ec2-spotfleet-launchtemplateconfig-syntax.yaml"></a>

```
[LaunchTemplateSpecification](#cfn-ec2-spotfleet-launchtemplateconfig-launchtemplatespecification): LaunchTemplateSpecification
[Overrides](#cfn-ec2-spotfleet-launchtemplateconfig-overrides):
  - [*LaunchTemplateOverrides*](aws-properties-ec2-spotfleet-launchtemplateoverrides.md)
```

## Properties<a name="w2922ab1c21c10c96d122c45b7"></a>

`LaunchTemplateSpecification`  <a name="cfn-ec2-spotfleet-launchtemplateconfig-launchtemplatespecification"></a>
The launch template\.  
*Required*: Yes  
*Type*: [FleetLaunchTemplateSpecification](aws-properties-ec2-spotfleet-fleetlaunchtemplatespecification.md)  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)

`Overrides`  <a name="cfn-ec2-spotfleet-launchtemplateconfig-overrides"></a>
Any parameters that you specify override the same parameters in the launch template\.  
*Required*: No  
*Type*: List of [LaunchTemplateOverrides](aws-properties-ec2-spotfleet-launchtemplateoverrides.md)  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)