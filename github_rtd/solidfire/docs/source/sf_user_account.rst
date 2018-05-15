Module documentation
====================
 class sf_user_account.SolidFireUserAccount

    We use this class to create, delete and update solidfire cluster admins user account.

    apply()

        This function checks if user account exists or not. If exists, then deletes the duplicate user account if does not exists, then creates an user account based on type of the user.

    create_cluster_user()

        This function creates a cluster user account under cluster admins.
        Raises:	duplicateErrorException

    create_ldap_user()

        This function creates an ldap user account under cluster admins.
        Raises:	duplicateErrorException

    delete_account()

        This function deletes the cluster admins user account based on cluster admins id.
        Raises:	duplicateErrorException

    get_user_account_by_id()

        This function returns details about the account. None if not found.

        :param name:self. :type name: int. :returns: int - if found. none - if not found.

    update_account()

        This function modifies the cluster admins user accounts based on cluster admin id.
        Raises:	duplicateErrorException

 




