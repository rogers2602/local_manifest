

Starting:
---------
# cd into your ROM's folder
mkdir -p .repo/local_manifests

    curl https://raw.githubusercontent.com/rogers2602/local_manifest/peridot-16/xiaomi.xml > .repo/local_manifests/xiaomi.xml
    curl https://raw.githubusercontent.com/rogers2602/local_manifest/peridot-16/gitlab.xml > .repo/local_manifests/gitlab.xml
    repo sync

