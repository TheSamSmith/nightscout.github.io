# New Nightscout Users

<span style="font-size:larger;">Interested in building a Nightscout DIY site?  
Make sure you read and undertand **[this](/#how-much-does-it-cost)** before starting.</span>

</br>

#### Currently fully documented solutions:

[Heroku Hobby account](../../vendors/heroku/new_user) with MongoDB Atlas.

Railway free Developer account with its own database or with a MongoDB Atlas (and [Heroku to Railway migration](../../vendors/railway/migration)).  
Use either of the methods until we find out which is easier: [Method 1](../../vendors/railway/new_user) or [Method 2](../../vendors/railway/new_user2).  

#### Work in progress solutions:

[Northflank](../../vendors/northflank/new_user) with its own database or with a MongoDB Atlas (can be used for migration).  
[Digital Ocean](../../vendors/digitalocean/new_user)    
[Synology](../../vendors/synology/new_user)  

#### External documentation to be consolidated:

[Google Cloud](../../vendors/google/new_user)  
[MVPS](../../vendors/MVPS/new_user)  
[Oracle](../../vendors/oracle/new_user)  
[Azure](../../vendors/azure/new_user)  

#### Exploration paths:

[Fly.io](../../vendors/fly.io/new_user/)

## Vendors comparison table

Click on the vendor logo.

<table style="padding:10px">
    <tr>
        <td>Vendor</td>
    	<td>Cost (USD)</td>
        <td>Web page</td>
        <td>Data base</td>
        <td>Complexity</td>
    </tr>
    <tr>
        <td><a href="/vendors/T1Pal/new_user/"><img src="../../vendors/img/T1Pal.png" align="center"></a></td>
    	<td>11.99$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="/vendors/10BE/"><img src="../../vendors/img/10BE.png" align="center"></a></td>
    	<td>max 4.99€/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>None</td>
    </tr>
    <tr>
        <td><a href="/vendors/heroku/new_user/"><img src="../../vendors/img/Heroku.png" align="center"></a></td>
    	<td>7$/month</td>
        <td>Yes</td>
        <td>No</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td><a href="/vendors/mongodb/atlas/#create-an-atlas-database"><img src="../../vendors/img/Atlas.png" align="center"></a></td>
    	<td>Free -></br>9$/month</td>
        <td>No</td>
        <td>Yes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td><a href="/vendors/railway/new_user"><img src="../../vendors/img/railway-app-logo.png" align="center"></a></td>
        <td>Free -></br>5$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td><a href="/vendors/northflank/new_user"><img src="../../vendors/img/northflank.png" align="center"></a></td>
        <td>Free -></br>???$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Medium</td>
    </tr>
<tr>
        <td><a href="/vendors/fly.io/new_user"><img src="../../vendors/img/flyio-logo.png" align="center"></a></td>
        <td>Free -></br>5$/month</td>
        <td>Yes</td>
        <td>No</td>
        <td>High</td>
    </tr>
    <tr>
        <td><a href="/vendors/google/new_user"><img src="../../vendors/img/GoogleCloud.png" align="center"></td>
        <td>Free -></br>$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>    <tr>
        <td><a href="/vendors/oracle/new_user"><img src="../../vendors/img/Oracle.png" align="center"></td>
        <td>Free -></br>$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>
    <tr>
        <td><a href="/vendors/MVPS/new_user"><img src="../../vendors/img/MVPS.png" align="center"></td>
    	<td>3$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>
    <tr>
        <td><a href="/vendors/digitalocean/new_user"><img src="../../vendors/img/DO.png" align="center"></a></td>
    	<td>6$/month</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>
    <tr>
        <td><img src="../../vendors/img/RPi.png" align="center"></td>
    	<td>Hardware</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>
    <tr>
        <td><a href="/vendors/synology/new_user/"><img src="../../vendors/img/Synology.png" align="center"></td>
    	<td>Hardware</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>High</td>
    </tr>
    <tr>
        <td><a href="/vendors/azure/new_user/"><img src="../../vendors/img/Azure.png" align="center"></a>	     </td>
        <td>variable</td>
        <td>Yes</td>
        <td>No</td>
        <td>High</td>
     </tr>
</table>

</br>

## Security and safekeeping

It's **highly important** you understand you have to take computer security seriously when setting up Nightscout. We assume you have full legal ownership of all data being stored in your installation of Nightscout and that there are thus no liabilities you'd need to respond to regarding the data. Depending on how you use Nightscout, an unauthorized user could cause harm by for example changing the CGM data shown by Nightscout. We have no evidence of this having ever happened to anyone, but to keep it that way, take the following guidelines to heart:

- Do not use the same password for all your accounts, and choose passwords that are not easy to guess.
- Do not use the API_SECRET for the Atlas database password.
- Do not use your Dexcom or CareLink user name or password for Nightscout components.
- Do not share the API_SECRET or other passwords to your accounts to others.
- Do not use Nightscout or any related applications on rooted and/or otherwise compromized devices, and ensure you always have the latest operating system and virus protection updates installed.

If you want to read more about Nightscout security, including about additional configuration options to make your installation more secure, please check our [security guide](../security/).

</br>

##### Record your information in a safe place.

You can either print this [pdf document](./NightscoutDataRecord.pdf) or edit the [Word version](./NightscoutDataRecord.docx), or this [Excel sheet](./NightscoutDataRecord.xlsx), to record all information during installation. Store it together securely with your diabetes documentation.

