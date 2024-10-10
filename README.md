# SWE_2021_41_2024_2_week_6
---
### Week 4 Assignment
- Link of my repository
https://github.com/mingyu27/SWE_2021_41_2024_2_week_4
- Description of my code

The isHappy function checks whether a number is a “happy number.”

- The get_next_number function calculates the sum of the squares of the digits of a number.
- If the number becomes 1, the function returns True, indicating it’s a happy number.
- Otherwise, it adds the number to the history set and calculates the next number using get_next_number.
- If the next number is already in history, it means a cycle has occurred, so the function returns False.
- The function keeps looping until it either reaches 1 (returns True) or detects a cycle (returns False).
---
### Week 5 Assignment
> ```shell
> docker exec ossp-container cat /etc/os-release
> ```
> - This commands docker to run ossp-container and run 'cat /etc/os-release' inside the ossp-container which prints information about OS
> > ```shell
> > PRETTY_NAME="Ubuntu 24.04.1 LTS"
> > NAME="Ubuntu"
> > VERSION_ID="24.04"
> > VERSION="24.04.1 LTS (Noble Numbat)"
> > VERSION_CODENAME=noble
> > ID=ubuntu
> > ID_LIKE=debian
> > HOME_URL="https://www.ubuntu.com/"
> > SUPPORT_URL="https://help.ubuntu.com/"
> > BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
> > PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
> > UBUNTU_CODENAME=noble
> > LOGO=ubuntu-logo
> > ```
> ```shell
> docker exec ossp-container git --version
> ```
> - This runs 'git --version' inside ossp-container which prints version of installed git.
>> ```shell
>> git version 2.43.0
>> ```
> ```shell
> docker exec ossp-container python3 --version
> ```
> - This runs 'python3 --version' inside ossp-container which prints version of installed python. 
>> ```shell
>> Python 3.12.3
>> ```
> ```shell
> ```shell
> docker inspect --format="{{ •HostConfig.Binds }}" ossp-container
> ```
> - This commands docker to check the bind mounts of ossp-container which prints any directory mappings of volumnes shared between host and the container.
>> ```shell
>> [/Users/hayden/ossp_host_dir:/mnt/ossp_container_dir]
>> ```
