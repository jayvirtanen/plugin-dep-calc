Plugin Dependency Calculator

Uses the CloudBees CI Update Center to calculate plugin versions and dependencies based on CloudBees CI version

outputs:

new_plugins.yaml - new plugins.yaml with dependency plugins included
plugins.txt - list of plugins and versions
uc.json - raw json of the update center contents

Requires:

JQ
YQ
DSQ
wget
