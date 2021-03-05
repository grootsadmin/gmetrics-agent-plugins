# To add gmetrics-agent binary plugins to remote host 

## Gmetrics-plugins, copy to "/groots/metrics/libexec"

- To copy gmetrics plugins from git to remote host's /groots/metrics/libexec directory

# Execution 

### Help Usage & get plugin list to copy

bash <(curl -Ls https://raw.githubusercontent.com/grootsadmin/gmetrics-agent-setup/[branch]/v5/bin/addplugin.sh) -h 

### To add plugins

$ bash <(curl -Ls https://raw.githubusercontent.com/grootsadmin/gmetrics-agent-setup/[branch]/v5/bin/addplugin.sh) -p (pluginname)

Ex:

$ bash <(curl -Ls https://raw.githubusercontent.com/grootsadmin/gmetrics-agent-setup/alpha/v5/bin/addplugin.sh) -p (pluginname)

- Plugins will get copied to groots/metrics/libexec directory

### Refer log

cat /var/log/groots/metrics/addplugin.sh.log