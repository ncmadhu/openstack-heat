# openstack-heat
commands to execute 
openstack stack create -t ubuntu_with_custom_security_grp.yaml --parameter key_name=heat_key --parameter image_id=UbuntuServer14.04 --parameter instance_type=m1.tiny TestUbuntu
openstack stack list
openstack stack event list TestUbuntu
openstack stack output show TestUbuntu host_ip
openstack stack delete TestUbuntu
