![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

# azure-security-templates
Useful templates of security policies, roles and runbooks to protect your Azure account

---

## Policies

I've added just 4 policies to start with, but I'll be adding more as I go along.

⚠️ Remember: You need to edit these policies to add your own values. 
Editable values are clearly marked.

* [Deny owner & contributor roles](policies/deny_owner_contributor_role.json)
* [Deny public critical ports](policies/deny_public_critical_ports.json)
* [Deny service principal with owner role](policies/deny_service_principal_with_owner_role.json)
* [Limit maximum users (3) with owner role](policies/limit_max_3_user_with_owner_role.json)


## Runbooks

In order to prevent most common security issues, I've added some runbooks to automate some tasks.

⚠️ Remember: You need to edit the runbooks to add your own values. 
Editable values are at the top of the file with a comment.

* [update_exposed_ssh_rdp.ps1](runbooks/update_exposed_ssh_rdp.ps1)
* [update_users_with_admin_roles.ps1](runbooks/update_users_with_admin_roles.ps1)

## Roles

I've added just 2 roles to start with, but I'll be adding more as I go along.

* [Owner sec](roles/owner-sec.json)
* [Contributor sec](roles/contributor-sec.json)

These roles are based on the default owner and contributor roles, but with some restrictions added. **Anyway these are not safe at all** but they are better than the default ones.

I'll be adding safer roles like: `Developer`, `Devops`, `Product Owner` or `Security Auditor`.

![](https://i.imgur.com/waxVImv.png)
# I'm are always open to your feedback🚀
# **[Contact Me🇻]**
* [Name: Nho Luong]
* [Telegram](+84983630781)
* [WhatsApp](+84983630781)
* [PayPal.Me](https://www.paypal.com/paypalme/nholuongut)
* [Linkedin](https://www.linkedin.com/in/nholuong/)

![](https://i.imgur.com/waxVImv.png)
![](Donate.jpg)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License🇻
* Nho Luong (c). All Rights Reserved.🌟
