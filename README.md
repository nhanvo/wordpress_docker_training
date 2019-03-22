Date: 2019/03/22
Author: NhanVo
Description: This is project training docker, wordpress, mysql, phpmyadmin.
1. Install docker images: wordpress, mysql, phpmyadmin
    - docker-compose up
2. Setup host for phpmyadmin
    - docker exec myslq container, enter command [hostname -i] will be display [172.17.0.2]
    - Enter into host of phpmyadmin is: [172.17.0.2]