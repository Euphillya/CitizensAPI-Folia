# How compile

## Install Repo CitizensAPI

```sh
sh script.sh updateUpstream
```

## Patch Repo CitizensAPI

```sh
sh script.sh applyPatches
```

## Compile jar

```sh
cd repo
mvn clean compile install
```