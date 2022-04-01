Deploy
========

Dodawanie repozytorium oprogramowania MySql
-------------------------------------------

1. Pierw należy pobrać najnowsze paczki na nasz system komendą

.. code-block:: console

   sudo apt update

2. Następnie trzeba zainstalować gnupg (Zamiennik oprogramowania kryptograficznego)

.. code-block:: console

   sudo apt install gnupg

3. Trzeba przejść do folderu tym czasowego (/tmp)

.. code-block:: console

   cd /tmp

4. Nastepnie należy pobrać paczki MySql

.. code-block:: console

   wget https://dev.mysql.com/get/mysql-apt-config_0.8.22-1_all.deb

5. Następnie trzeba dodać pliki konfiguracyjne MySql

.. code-block:: console

   sudo dpkg –i mysql-apt-config*

6. Ponownie sprawdzamy dostępność paczek

.. code-block:: console

   sudo apt update

Instalacja
----------

1. Za pomocą komendy instalujemy MySql server

.. code-block:: console

   sudo apt install mysql-server

2. Nastepnie sprawdzamy status naszego MySql

.. code-block:: console

   sudo systemctl status mysql

3. Na końcu instalujemy bezpieczną instalacje MySql

.. code-block:: console

   mysql_secure_installation

