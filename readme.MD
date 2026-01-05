#VPC Module
This module is developed for Practice purpose. Projects follow this module to create VPC.

##Inputs
* Project (required) - Users should specify their project name
* environment (required) - Users should specify their environment
* cidr_block (optional) - Users can provide their CIDR block. default is 10.0.0.0/16
* public_subnet_cidrs (required) - Users can provide their public subnet cidrs.
* private_subnet_cidrs (required) - Users can provide their private subnet cidrs.
* database_subnet_cidrs (required) - Users can provide their database subnet cidrs.

##Outputs
* vpc_id - Exports vpc ID created
* public_subnet_ids - Exports public subnet ids