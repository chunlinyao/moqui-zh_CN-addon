# moqui-zh_CN-addon
This is a add-on component for moqui, it contains the county level geo data of china and l10n message for Simplified Chinese.

县级行政区划数据太多，放在了extra-data目录下，类型是`extra`，需要单独载入的话运行`ln -s ../extra-data/GeoChnCountiesData.xml data/`,然后是`java -jar moqui.war -load -components=moqui-zh_CN-addon -types=extra`。
