# ROBLOX Rank Application System - Admin Panel Access Guide

## Overview
This guide explains how to give access to the Admin Panel so other developers and moderators can help manage applications.

---

## Step-by-Step Instructions

### Step 1: Open Admin Panel
1. Go to **form-admin.html** in your browser
2. You should see the ROBLOX Admin Panel dashboard
3. Look for the **"👥 User Management"** tab at the top

### Step 2: Switch to User Management Tab
1. Click on the **"👥 User Management"** tab (right next to "📋 Applications")
2. You'll see a form titled **"➕ Add New User"**

### Step 3: Add a New Team Member
Fill in the form with the developer/moderator's information:

```
Username / Discord ID: Developer#1234
Email: developer@example.com
Role: Choose one:
  - Reviewer (Can view applications only)
  - Moderator (Can approve/reject applications)
  - Admin (Full access to everything)
```

### Step 4: Click "Add User"
- The user will be added to your team instantly
- They'll appear in the "👥 Team Members" section below
- They can now access the admin panel

---

## Example: Adding a Moderator

**Scenario:** You want to add your friend "TowerKing" as a moderator

**Steps:**
1. Go to form-admin.html
2. Click "👥 User Management" tab
3. Fill in the form:
   ```
   Username / Discord ID: TowerKing#5555
   Email: towerking@example.com
   Role: Moderator (Can approve/reject applications)
   ```
4. Click "Add User"
5. Success! ✓ User "TowerKing#5555" added successfully as moderator!

**Result:**
- TowerKing can now access the admin panel
- TowerKing can view all applications
- TowerKing can approve or reject applications
- TowerKing CANNOT manage other users (only Admins can do that)

---

## Example: Adding a Reviewer

**Scenario:** You want to add a volunteer "CasualReviewer" who just views applications

**Steps:**
1. Go to form-admin.html
2. Click "👥 User Management" tab
3. Fill in the form:
   ```
   Username / Discord ID: CasualReviewer#9999
   Email: reviewer@example.com
   Role: Reviewer (Can view only)
   ```
4. Click "Add User"
5. Success! ✓ User "CasualReviewer#9999" added successfully as reviewer!

**Result:**
- CasualReviewer can view all applications
- CasualReviewer can see application details
- CasualReviewer CANNOT approve/reject applications
- CasualReviewer CANNOT manage users

---

## Example: Adding an Admin

**Scenario:** You want to add a co-creator "DevLead" with full control

**Steps:**
1. Go to form-admin.html
2. Click "👥 User Management" tab
3. Fill in the form:
   ```
   Username / Discord ID: DevLead#2222
   Email: devlead@example.com
   Role: Admin (Full access)
   ```
4. Click "Add User"
5. Success! ✓ User "DevLead#2222" added successfully as admin!

**Result:**
- DevLead has FULL ACCESS
- DevLead can view and manage all applications
- DevLead can approve/reject applications
- DevLead can add/remove other users
- DevLead can change user roles

---

## Current Team Members

Your current team (visible in User Management tab):

| Name | Email | Role | Status |
|------|-------|------|--------|
| You (Creator) | admin@roblox.dev | Admin | Active |
| Developer#5678 | dev1@roblox.dev | Moderator | Active |
| Reviewer#1111 | reviewer@roblox.dev | Reviewer | Active |

---

## Managing Existing Users

### Edit a User's Role
1. Click "👥 User Management" tab
2. Find the user card you want to edit
3. Click the **"Edit"** button on their card
4. Enter the new role (admin/moderator/reviewer)
5. Role updated instantly!

**Example:**
```
Editing Developer#5678:
Current role: Moderator
New role: Admin
✓ Role updated to: Admin
```

### Remove a User
1. Click "👥 User Management" tab
2. Find the user card you want to remove
3. Click the **"Remove"** button on their card
4. Confirm the removal in the popup
5. User removed from team!

**Example:**
```
Removing CasualReviewer#9999?
Are you sure you want to remove "CasualReviewer#9999" from the team?
[Yes] [No]
✓ User removed successfully
```

---

## Role Permissions Summary

### 👁️ Reviewer
- ✓ View all applications
- ✓ See application details
- ✓ Check application status
- ✗ Cannot approve/reject
- ✗ Cannot manage users

### 🔧 Moderator
- ✓ View all applications
- ✓ See application details
- ✓ Check application status
- ✓ Approve applications
- ✓ Reject applications
- ✗ Cannot manage users

### ⭐ Admin
- ✓ View all applications
- ✓ See application details
- ✓ Check application status
- ✓ Approve applications
- ✓ Reject applications
- ✓ Add new users
- ✓ Edit user roles
- ✓ Remove users

---

## How Others Access the Panel

Once you've added them as a user, they can:

1. **Go to form-admin.html** (bookmark it for easy access)
2. **See the dashboard** with all applications
3. **Review and manage** applications based on their role
4. **Filter applications** by status, rank, or search reference number
5. **View full application details** and decide to approve or reject

---

## Quick Tips

✅ **Add Team Members Early** - Don't wait until you're overwhelmed with applications
✅ **Use Appropriate Roles** - Give Reviewer role to trusted volunteers, Moderator to experienced members
✅ **Keep Admins Limited** - Only give Admin access to co-creators/trusted leads
✅ **Regular Updates** - Review team roles and permissions regularly
✅ **Communication** - Let users know they've been added and what they can do

---

## What's Next?

- ✓ Added users to the system
- ✓ Assigned them appropriate roles
- ✓ They can now access form-admin.html
- → **Now they can help review and approve applications!**

---

## Support & Questions

For any issues or questions about:
- Adding users
- Changing roles
- Removing team members
- Application management

Check the Admin Panel → look for help documentation or contact the system administrator.

---

**Last Updated:** November 29, 2025
**ROBLOX Rank Application System v1.0**
