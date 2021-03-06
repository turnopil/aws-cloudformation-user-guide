# AWS::MediaLive::Channel ArchiveContainerSettings<a name="aws-properties-medialive-channel-archivecontainersettings"></a>

Configures the container in the output group\. This element belongs to ArchiveOutputSettings\.

## Syntax<a name="aws-properties-medialive-channel-archivecontainersettings-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-medialive-channel-archivecontainersettings-syntax.json"></a>

```
{
  "[M2tsSettings](#cfn-medialive-channel-archivecontainersettings-m2tssettings)" : M2tsSettings
}
```

### YAML<a name="aws-properties-medialive-channel-archivecontainersettings-syntax.yaml"></a>

```
  [M2tsSettings](#cfn-medialive-channel-archivecontainersettings-m2tssettings): 
    M2tsSettings
```

## Properties<a name="aws-properties-medialive-channel-archivecontainersettings-properties"></a>

`M2tsSettings`  <a name="cfn-medialive-channel-archivecontainersettings-m2tssettings"></a>
Include this element if you want to set up the output in an MPEG2 TS stream\.  
*Required*: No  
*Type*: [M2tsSettings](aws-properties-medialive-channel-m2tssettings.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)