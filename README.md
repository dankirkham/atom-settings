# atom-settings
```shell
apm install sync-settings sync-settings-git-location
CONFIG_FILE=~/.atom/config.cson
echo \"\*\": > $CONFIG_FILE
echo "  \"sync-settings\":" >> $CONFIG_FILE
echo "    useOtherLocation: true" >> $CONFIG_FILE
echo "  \"sync-settings-git-location\":" >> $CONFIG_FILE
echo "    gitUrl: \"https://github.com/dankirkham/atom-settings.git\"" >> $CONFIG_FILE

```
