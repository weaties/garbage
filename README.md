keystone endpoint-create --service=nova --publicurl=http://10.10.10.2:8774/v2/%\(tenant_id\)s --internalurl=http://10.10.10.2:8774/v2/%\(tenant_id\)s --adminurl=http://10.10.10.2:8774/v2/%\(tenant_id\)s

keystone endpoint-create --service=cinder --publicurl=http://10.10.10.2:8776/v1/%\(tenant_id\)s --internalurl=http://10.10.10.2:8776/v1/%\(tenant_id\)s --adminurl=http://10.10.10.2:8776/v1/%\(tenant_id\)s

keystone endpoint-create --service=cinderv2 --publicurl=http://10.10.10.2:8776/v2/%\(tenant_id\)s --internalurl=http://10.10.10.2:8776/v2/%\(tenant_id\)s --adminurl=http://10.10.10.2:8776/v2/%\(tenant_id\)s

keystone endpoint-create --service=glance --publicurl=http://10.10.10.2:9292 --adminurl=http://10.10.10.2:9292 --internalurl=http://10.10.10.2:9292

keystone endpoint-create --service=swift --publicurl=’http://10.10.10.2:8080/v1/AUTH_%(tenant_id)s’ --internalurl=’http://10.10.10.2:8080/v1/AUTH_%(tenant_id)s’ --adminurl=’http://10.10.10.2:8080/v1’

keystone endpoint-create --service=keystone --publicurl http://10.10.10.2:5000/v2.0 --internalurl http://10.10.10.2:5000/v2.0 --adminurl http://10.10.10.2:35357/v2.0

keystone endpoint-create --service=neutron --publicurl http://10.10.10.2:9696 --internalurl http://10.10.10.2:9696 --adminurl http://10.10.10.2:9696
