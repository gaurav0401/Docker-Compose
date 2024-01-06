<h1>Docker Compose</h1>


<p>Docker Compose is a tool which used for defining and running multi-container Docker applications. <br> It is used to deploy docker applications. </p>



<li>Docker-compose file  has .yml or .yaml extension or we can say it is a yaml format file.</li>
<li><b>YAML file:</b>YAML is a human-readable data serialization language that is often used for writing configuration files.</li>
<li><b>Format of YAML file:</b> <a href="https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started">click here</a>  </li>


<h3>How to create a  compose file for docker</h3>
<ul>
    <li><b>create 'docker-compose.yml' file</b></li>
    <li><b>'version':</b>if specifies which version of compose we are using.</li>
    <li><b>'services':</b>it specifies which services we are using in our application like api , web , databases etc</li>
    <li><b>build:</b>It specifies where to find the docker file for specific service.</li>
    <li><b>image:</b>It specifies which image to be used for service e.g in case of db it may be mysql or mongo etc.</li>
    <li><b>ports:</b>It defines which ports to be used to run application. </li>
    <li><b>environment:</b>it defines  which environment to be used for a services , we can define more than one environment variables.</li>
    <li><b>volumes:</b>It defines the volumes for application.</li>
    <li><b>command:</b>it defines  which commands to be run during building an image.</li>
    <li><b>container_name:</b>It defines name for a container.</li>
    
</ul>

<h3>How to build images using compose file</h3>
<ul>
    <li><b>docker-compose build:</b> used to build image from compose file.</li>
    <li><b>docker-compose  up --build:</b> It is used to build images from the compose file and then run containers of that image.</li>
    <li><b>docker-compose  down:</b> It is used to stop running containers but images still remains.</li>
</ul>
