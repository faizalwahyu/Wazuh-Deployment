Installation

You can easily install Wazuh using this command, which runs the All-in-One installation script directly from the official Wazuh packages repository.

    curl -sO https://packages.wazuh.com/4.12/wazuh-install.sh && sudo bash ./wazuh-install.sh -a

By running this single command, you perform a quick and automated installation of a complete Wazuh stack on your server, suitable for testing or small-scale deployments.

After running the installation script, you will receive a username and password displayed in the terminal. These credentials allow you to log in to the Wazuh dashboard.
Open your web browser and navigate to the IP address (or URL) shown in the installation output.
