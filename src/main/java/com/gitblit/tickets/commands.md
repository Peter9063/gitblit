#### To review with Git

To review an updated patchset

    git fetch && git checkout ${ticketBranch} && git pull --ff-only

To review a rewritten patchset

    git fetch && git checkout ${ticketBranch} && git reset --hard origin/${ticketBranch}

