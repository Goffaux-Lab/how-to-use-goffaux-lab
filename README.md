# How to use Goffaux-Lab
This is the lab's shared github space. We should upload any code and documents
that could be useful for anyone in the lab to be able to use.

## Overview of the workflow Github repositories can then be **forked** between
accounts (i.e. create a copy) so that others can use them too. The original
copy is called the **upstream**. So you can **fork** a repository from your
personal github account the Goffaux-Lab account, or **fork** a repository from
Goffaux-Lab account to yours.

On your personal github account you can make changes (or **commits**) to the repositories as you
please. These **commits** can easily be synchronised back to the Goffaux-Lab
account submitting a **pull request**.

If you're working on a **fork** of a repository on your personal account, and
meanwhile someone makes **commits** to the repository on the Goffaux-Lab account
(i.e. submits a **pull request** that is accepted), you can easily synchronise
your **fork** of the repository with the updated Goffaux-Lab account (this is
called **fetch-upstream**).

### Sharing your work

In order to make one of your personal repositories appear on the Goffaux-Lab
page, go to your repository:

 1. Click the **fork** button
 2. Make sure the Goffaux-Lab is selected as the destination
 3. Click 'create fork'

![fork_from_personal_to_lab](images/fork_from_personal_to_lab.png)

Once the **fork** has completed, the repository will appear on the Goffaux-Lab
page. Clicking on it we notice some things: 

 1. It displays that the repo was originally forked from your personal account
    (the original repository is the **upstream**).
 2. We have the option to synchronise the **fork** by doing **fetch upstream**.
    This would copy over any new **commits** that have accumulated on the
    original repository since the **fork**.

Immediately after **forking**, there won't be any new **commits**.

![after_forking_from_personal_to_lab](images/after_forking_from_personal_to_lab.png)

If we make a **commit** (i.e. add some more code or fix a bug) in the
**upstream** repository (i.e. on our personal account). Then come back to look
at the **fork** on Goffaux-Lab, we see that:

 1. The repo knows that it is now 1 commit behind the **upstream**.
 2. Have available options with **fetching upstream**
 3. We can compare the differences between the **fork** and the **upstream**.
 4. Or we can immediately **fetch** those **commits** and **merge** them into
    the **fork** (i.e. synchronise the repositories).

![fetch_upstream](images/fetch_upstream.png)

Comparing the files looks like this:

![compare_upstream](images/compare_upstream.png)

### Using/Updating existing work
If you want to use a repository on Goffaux-Lab, go to the repository and
**fork** it to your personal account. Then you can **clone** the repository
from your own account onto your local machine. You are now free to make
**commits** to the **fork** of the repository.

