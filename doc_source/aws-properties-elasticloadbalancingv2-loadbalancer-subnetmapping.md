# Elastic Load Balancing V2 SubnetMapping<a name="aws-properties-elasticloadbalancingv2-loadbalancer-subnetmapping"></a>

<a name="aws-properties-elasticloadbalancingv2-loadbalancer-subnetmapping-description"></a>The `SubnetMapping` property type specifies the ID of a subnet to attach to an Application Load Balancer or a Network Load Balancer\.

<a name="aws-properties-elasticloadbalancingv2-loadbalancer-subnetmapping-inheritance"></a> `SubnetMappings` is a property of the [AWS::ElasticLoadBalancingV2::LoadBalancer](aws-resource-elasticloadbalancingv2-loadbalancer.md) resource\. 

## Syntax<a name="w2922ab1c21c10d120c27c20b7"></a>

### JSON<a name="aws-properties-elasticloadbalancingv2-loadbalancer-subnetmapping-syntax.json"></a>

```
{
  "[SubnetId](#cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-subnetid)" : String,
  "[AllocationId](#cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-allocationid)" : String
}
```

### YAML<a name="aws-properties-elasticloadbalancingv2-loadbalancer-subnetmapping-syntax.yaml"></a>

```
[SubnetId](#cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-subnetid): String
[AllocationId](#cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-allocationid): String
```

## Properties<a name="w2922ab1c21c10d120c27c20b9"></a>

`SubnetId`  <a name="cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-subnetid"></a>
The ID of the subnet\.  
*Required*: Yes  
*Type*: String  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)

`AllocationId`  <a name="cfn-elasticloadbalancingv2-loadbalancer-subnetmapping-allocationid"></a>
\[Network Load Balancer\] The ID that represents the allocation of the Elastic IP address\.  
*Required*: Yes  
*Type*: String  
*Update requires*: [No interruption](using-cfn-updating-stacks-update-behaviors.md#update-no-interrupt)