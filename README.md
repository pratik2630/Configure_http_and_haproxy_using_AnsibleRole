# Configure_http_and_haproxy_using_AnsibleRole
TASK DESCRIPTION:🔅Create an ansible role myapache to configure Httpd WebServer.  🔅Create another ansible role myloadbalancer to configure HAProxy LB.  🔅We need to combine both of these roles controlling webserver versions   and solving challenge for host ip's  addition  dynamically over  each Managed  Node  in  HAProxy.cfg file.


Run main.yml file on your system to work both playbook at a time.
command: ansible-playbook main.yml


To access webpage you have to use loadbalancer's ip address
