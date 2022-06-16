## Docker

### Things you will learn about docker
- Build and run an image as a container.
- Share images using docker Hub.
- Deploy Docker applications using multiple containers with a database.
- Running applications using Docker Compose.

Created a docker file then from that file we build an image names getting-started then from that image i builded a container at port 3000.

update the application
update the file app.js
then rebuild the image
then started new container
only one process on the machine(containers included) can listen to a specific port.

credentails store

### Persist the DB

**Volumes** provide the ability to connect specific filesystem paths of the container back to the host machine.
- If a directory in the container is mounted, changes in that directory are also seen on the **host macchine.**
  
create volume *docker volume create todo-db*
*docker run -dp 3000:3000 -v todo-db:etc/todos getting-started.*

### where is Docker actually storing my data when i use a named volume ?
command : docker volume inspect todo-db
**Mountpoint**