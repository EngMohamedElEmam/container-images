Container Images Repository

All DockerImages/NPM Packages/Maven artifacts can be viewed under "packages" tab

If you need to access these images for your deployments. Use this token - 524ea08fef8c273c2f739920a8427b502f7dc789
Commands Used
Create docker images using build

    docker build . -t hello-world:v1

Tag the images to the package registry path

    docker tag hello-world:v1 docker.pkg.github.com/engmohamedelemam/container-images/hellow-world:v1


Push the images to the Github package registry

    docker push docker.pkg.github.com/engmohamedelemam/container-images/hellow-world:v1

