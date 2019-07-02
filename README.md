# OcelotAndSwagger
Show swagger api documentation of each service in the ocelot gateway swagger ui

## Things that annoying me
The thing is, each service must know that its behind a gateway and it must define its routes under the gateway sub route in controllers. I prefer a way that services to be standalone and doesnt need to know their place in the production area.
