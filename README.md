# wildfly-proxy
Repository that contains patches in order to run Apache as a reverse proxy for the wildfly application server. 
It covers all upgrade mechanisms that are required to provide remoting (EJB, JNDI) as well as JMS with ActiveMQ Artemis.

This as been tested with wildfly 10.1.0 which was patched with https://github.com/wildfly/wildfly/pull/10082 as this fixes an
issue in ActiveMQ Artemis ignoring the client mapping attribute.

This patch was created against Apache 2.4.25.
