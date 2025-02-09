# Aypos-Controller-Api

# steps
# 1 - configure openstack_configs.py using admin-openrc.sh or other api config file
# 2 - run create_flavors.py Python file and create random flavors.
# 3 - run configs.py and get network configurations then configure network_name, ip_number, use_zone checking on output
# 4- configure prometheus_vm name, openrc file location, image name and other configuration needed 
# 5- install required python libraries, openstack library is alredy installed on controller machine
# 6- run migration_api.py at the background $ nohup python3 migration_api.py &
