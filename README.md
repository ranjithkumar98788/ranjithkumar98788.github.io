summary: My Homework Codelab
id: my-homework-codelab
categories: Homework
environments: Web
status: Published
feedback link: https://github.com/your-repo/issues

# 1. Before You Begin
Try to answer the question, "Why does this codelab exist?" This should be one sentence.
## Prerequisites
To perform this codelab, you must have:

A Google email address (either your GVSU Google email account or a personal Gmail account.
A Google Cloud coupon sent by the instructor (or, if you are not from GVSU, a free-tier Google Cloud account).

## What You'll Do
1. Create a Google Cloud account
2. Setup a billing account and project
3. Create a free-tier virtual machine that you can always leave on

## What you'll need
Up-to-date browser
Working internet connection

## Note!
All cloud providers have a tendency of updating their interface ... often! If what you see doesn't match my screenshots exactly feel free to click around and explore - they should be at least similar.


# 2. Account Setup
For this lab we are going to work with Google Cloud to setup your account, a billing account, a project, and a micro-instance of a virtual machine.

As this is your first lab with me, and I'm not physically there to walk you through this, please **read this manual carefully and follow along**. There will be homework questions seeded throughout this document asking you to take a screenshot here or there, report information, etc., and you won't be able to go back to it without starting over.

To nip the question in the bud, yes, you must provide an answer to all questions. If you missed a step, then that is on you to fix. Again, **read carefully**.

You can create as many VMs as you want, but keep in mind that your account will be charged for each moment a VM is online. **Note that you should never put your personal credit card information into the site. This is 100% free for you**.

The reason we're using a micro-instance is that it is free to your account, as long as you don't send/receive too much data. More info here on that: http://cloud.google.com/free.

## Coupon Setup
You should have received an email forwarded from myself containing information for signing up for Google Cloud. Your GVSU Google email is required for the first form, as that will send you the coupon.

The second email you get will be a coupon code to redeem. **Ensure that the account you are logged in as (top right corner) matches the email address you're redeeming from.**

Accept the agreement and continue. You should now have $50 in your Google Cloud account.

_If you see a 'Your free trial is waiting' banner at the top, click 'Dismiss' as we don't want to use that. You have free credits as part of the course. Once you are done with the class feel free to use those!_

Congrats, your account is setup.

# 3. Google Cloud Environment
You should have a screen that looks similar to this screenshot:



There are a few things to notice here. The panel on the left lists out *all* of the Google Cloud products you can work with.

**Note that the majority are not activated!** This means that, if you want to use one, you first need to Enable it.

This preference helps both with keeping costs down and security up.

The panel on top has a few key points to become intimately familiar with.



First, the drop down with 'My First Project' lists out all the Projects associated with your account. 'My First Project' is automatically created for you when your billing account is created. You can create more projects as you desire, however **they must be linked to a billing account**. Meaning, each time *something* happens on your project, it is charged to a billing account.

The next object is the search bar. This enables you to quickly find *anything* within Google Cloud and should be your first stop if you don't know where something is.

The >_ button activates Cloud Shell. We will cover this in another module, but it is essentially a Linux shell for interacting with Google Cloud.

The circular button next to it with a 1 inside is the list of current notifications. Refer to it whenever you do something, as it will communicate the server status to you. If you click it now, you will probably see a notification that 'My First Project' was created.



If it is spinning, then Google is working in the background. You can click it for more information.

## View Billing Information
In the left panel, click 'Billing' (or search for Billing). This will bring you to your account overview and tell you how much money you have left in your account.

**AS A REMINDER, NEVER PUT YOUR CREDIT CARD IN. IF YOU RUN OUT OF CREDITS CONTACT ME AND I WILL SEND YOU ANOTHER COUPON.**

_(Non-GVSU students, you're on your own)._

You should see something like this in the bottom-right corner (you may need to scroll down to Credits in the left side, and then it will possibly be a horizontal bar -- this area has been recently updated):


