# TOSCA uses the concept of service templates to describe cloud workloads. 

Topology and Orchestration Specification for Cloud Applications (TOSCA) is the standard domain specific language (DSL) defined by OASIS to orchestrate cloud applications. It defines the topology of the cloud based services, their components and relationship between them. Cloud Manager can orchestrate and deploy a network service that is defined by a TOSCA network service descriptor. The TOSCA NSD is a Cloud Service Archive (CSAR) file with csar extension defined by OASIS 

and is different from the TOSCA VNF packages, which follow the ETSI GS NFV-SOL 003 specification.The NSDs are defined in the YAML 

The TOSCA NSD is CSAR file has a csar extension. The CSAR file is a zip file that contains all the data needed according to the TOSCA specification. When you define a service configuration in a TOSCA package, you can instantiate the package multiple times to create similar services in your environment. When you instantiate the service, you change values to make each instance unique.

Cloud Manager can upload (onboard) and manage the CSAR files and deploy (instantiate) network services based the contents of the CSAR files. The files must contain the files and directories described required by Cloud Manager. A CSAR is a zip file containing at least two directories, the TOSCA-Metadata directory and the Definitions directory.
