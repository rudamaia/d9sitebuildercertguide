[<< Previous](terminology.md)
# The User 1 Account

### What is the user 1 account?

During the installation of your site, you created the first user account. Each user account internally has a numeric user ID, and since the ID of this user is one, it is commonly referred to as the _user 1_ account. This user account is special, because independent of what roles it is assigned, someone logged in as user 1 has permission to do all actions on the site, including viewing and editing all content, editing any user account, changing site configuration, installing and uninstalling modules, and running the update script.

Because of this level of permission, some people refer to this account as the _root user_, similar to the "root" user account that has full administrative permissions in Linux and other operating systems.

It is usually better to make separate accounts for each administrative user, giving them the _Administrator_ role, rather than having all administrative users log in using the user 1 account. There are several reasons for this:

*   Some actions and updates on the site are logged, and if everyone uses the same account, it is difficult to know who did them if you have questions.
*   The _Administrator_ role permissions can be modified to be safer than the full permissions of the user 1 account, so that people do not inadvertently change site features that shouldn’t be changed.
*   People’s responsibilities on a site may change over time. With ordinary user accounts, this can be mirrored in permissions by assigning or unassigning roles to their user accounts. If they are all using the user 1 account, this is more difficult.
*   On some sites, the author of content or comments is displayed or tracked, and if everyone uses the same account to create content, it is difficult to know who created the content.

It is not possible to delete the user 1 account from the administrative user interface. It would be possible to do with a database query, but it could cause problems in your site and is not advisable.