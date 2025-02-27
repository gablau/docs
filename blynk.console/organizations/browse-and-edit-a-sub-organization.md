# Browse & Edit a Sub-Organization

Login to Blynk as a user with a role and permissions that will allow you to perform your intended actions.  The ‘Admin’ role with default permissions is sufficient.

Click on the sidebar ‘Organizations’ and a list of your organizations will appear.

{% hint style="info" %}
Note that only the first level of organizations are displayed.
{% endhint %}

Click on a particular organization and then the details are displayed in the tabs ‘Info’, ‘Templates’, ‘Users’, ‘Locations’.

Navigate to ‘Search -> ‘ORGANIZATIONS’ to switch to a sub-organization, enabling you to then see any third level or deeper sub-organizations. It also provides a useful way to see device and user assignment to organizations.

Navigate to ‘Settings -> ORGANIZATION SETTINGS -> Locations’, or ‘Search -> LOCATIONS’ to see them, add new locations, assign users, and delete locations.

### Add Templates to a Sub-Organization

Under the ‘Templates’ tab, you will only see the templates that have been enabled for your organization.

In order to see what other templates are available to be enabled, click the ‘Edit’ button at the upper right of the Blynk.Console.

After a template has been enabled for your sub-organization, the related devices may be [transferred](https://docs.blynk.io/en/blynk.console/devices/actions-with-devices#move-device-to-another-organization-within-your-hierarchy) to another user.

{% hint style="info" %}
Enabling a template for a sub-organization doesn’t perform any automatic device transfers, but it does allow devices to be transferred.
{% endhint %}

### Invite Users to a Sub-Organization

You can dynamically invite users to an organization that don’t currently have a Blynk account and assign them the [roles](../settings/access.md) of ‘Admin’, ‘Staff’, or ‘User’.  Existing Blynk members will need to be [transferred](browse-and-edit-a-sub-organization.md#how-to-transfer-a-user-to-another-organization).

Navigate to Main menu -> Organizations, select the organization. Here from the ‘Users’ tab, you may invite new users to add them to the organization, and you can delete users.

The other way to add a user to an organization is through Search -> Organizations. Select an existing organization. Click the ‘...’ link at the top right of the page and choose the option ‘Manage Users’.  From this page you can click the ‘+ Invite’ button at the top of right of the screen to add a user that doesn’t have a Blynk account to the organization.&#x20;

The user will receive an invitation by email and must click on the link in the email to set a password within 30 days. The user’s status will appear as ‘Pending’ until they click on that email link and set a password.

### How to Transfer a User to Another Organization

Existing Blynk members can be transferred from one organization to another via Search -> Users -> All -> Actions -> Transfer User, or Settings -> ORGANIZATION SETTINGS -> Users.

{% hint style="info" %}
Users can only be transferred within the same hierarchy. E.g.: If a user has a Blynk account, that's not within your organization structure, they will have to delete their account prior to being added to your organization or use a different email that hasn't been in use on Blynk.&#x20;
{% endhint %}

To transfer a user that is currently a Blynk member, navigate to  Search -> Users -> All -> Actions, and choose the ‘Transfer User’ option. Enter the email address of the administrator for the destination organization. You may change the role for the user, and optionally transfer all owned devices. The user transferred, and the admin for the destination organization will automatically receive an email notification of the user transfer.

![](https://lh6.googleusercontent.com/lheniT04JM8J9tggh3d3aG7aQbwN9s9QHPZ9E7plcDSGeQjkOc6noBEXHYGI\_J6lArBnLYV1oK1gjsrXOTrFB\_9TX8zpM2J06SFqxL3QSr5eNQOHz9\_6A\_bYH9lhMjE9agmtdLtiUsMQRwsjXgrfEiVZHFLD9Val0ulyJXzgJgNuw9FpXzr6EssNN\_vUig)   ![](https://lh5.googleusercontent.com/VR1k0YxzWlflnCNJnJLxTe3x0dy0sa6pbzFiNtsNoQ0CKeZRZI\_K0QN1WlN72k5H60yYeB66qlDR7XgsB3MaDB6Roi6hQPk4\_xRswMEEwnkfxt6t\_tWzmwI4qi3qO8egk7b\_HLxg7ja-NdYZ7HviiIDJcfs13v9e4091OMk1z\_uzoV8PMmEy\_DvAvXVnvQ)

{% hint style="danger" %}
WARNING:  If you transfer the only ‘Admin’ user in a sub-organization to another organization, then you will need to assign another user with the ‘Admin’ role that is not a Blynk member.
{% endhint %}

### Switching to a Sub-Organization

You can make a particular sub-organization active from Search -> ORGANIZATIONS and then under the list, hover your mouse over the organization name and click on the ‘Switch to’ link. On doing that you will view the sub-organization exactly like the users of this sub-organization would, which will make troubleshooting far easier.

<figure><img src="../../.gitbook/assets/switch-to.png" alt=""><figcaption></figcaption></figure>

Once you switch to a sub-organization, you will see the templates, devices, and users assigned to the sub-organization. The scope of devices each sub-organization user will see depends on their [device permissions](../settings/access.md#devices).

In this mode you can also perform all actions on the sub-organization as if you were their admin.

{% hint style="info" %}
You can navigate back to your root organization by clicking the Blynk logo at the top of the sidebar menu (top left corner).
{% endhint %}

### How to Move a Device to a Sub-Organization

Every device has one owner assigned to it. You can allow multiple members view and manage the same device by adjusting the device permissions by role, and assigning those roles to members.

The easiest way to move a device within your org structure is to [change its ownership](../devices/actions-with-devices.md#device-transfer). You can transfer ownership from one member to another by email address.

{% hint style="info" %}
The device will automatically be moved to the same organization (or sub-organization) within your hierarchy that the member assigned to it belongs to.
{% endhint %}

### How to Assign a Device to a User

Learn more about [device sharing](../devices/device-sharing.md) options. You can view device ownership from the [Blynk.Console](broken-reference) and from a Blynk.App (upon selecting a device tap on (...) and select the Information tab). \


