# cfn-modules: RDS instance

This is an internal module. Have a look at the following modules instead:

* [rds-postgres](https://www.npmjs.com/package/@cfn-modules/rds-postgres)
* [rds-mysql](https://www.npmjs.com/package/@cfn-modules/rds-mysql)

## Limitations

* Scalable: RDS instances capacity (CPU, RAM, network, ...) is limited by design
* Monitoring: Network In+Out is not monitored according to capacity of instance type
