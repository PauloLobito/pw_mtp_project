# **Branching strategies**

## **What is a branching strategy?**
Branches are used to develop different things at the same time, since features to bug fixes. Most of the branches are merged to the Main/Master ate the end of their cicle. So branching strategy is the strategy that teams adopt to develop their projects more easily.

## **Git Flow**
Git-Flow is a branching strategy that aims to cover various scenarios. It defines specific branch responsibilities, the life-cycle involves branching off from develop, integrating features, creating release branches for testing, merging into main/master, and tagging versions.

![](/images/gitflow.png)

Pros:
- Well-suited for large teams and aligning work across multiple teams.
- Effective handling of multiple product versions.
- Clear responsibilities for each branch.
- Allows for easy navigation of production versions through tags.

Cons:
- Complexity due to numerous branches, potentially leading to merge conflicts.
- Development and release frequency may be slower due to multi-step process.
- Requires team consensus and commitment to adhere to the strategy.

## **GitHub-Flow:**
GitHub-Flow simplifies Git-Flow by eliminating release branches. It revolves around one active development branch that is directly deployed to production. Features and bug fixes are implemented using long-living feature branches. Better for smaller and teams as they don't have many branches. The main idea behind this model is keeping the master code in a constant deployable state and hence can support continuous integration and continuous delivery processes.

![](/images/github-flow.png)

Pros:
- Faster feedback cycles and shorter production cycles.
- Ideal for out of sync work in smaller teams.
- Agile and easier to comprehend.

Cons:
- Merging a feature branch implies it is production-ready, potentially introducing bugs without proper testing.
- Long-living branches can complicate the process.
- Challenging for larger teams due to a lot of merge conflicts.
- Supporting multiple release versions at the same time is difficult.

## **GitLab Flow**
GitLab Flow is a balance between the two before. It has GitHub-Flow’s simplicity while introducing additional branches representing staging environments before production. The main branch still represents the production environment. With GitFlow, developers create a develop branch and make that the default while GitLab Flow works with the main branch right away.

![](/images/gitlab-flow.png)

Pros:
- Can handle multiple release versions or stages effectively.
- Simpler than Git-Flow.

Cons:
- Complexity increases when maintaining multiple versions.
- More complex compared to GitHub-Flow.

## **Trunk Based Development**

Trunk Based Development promotes a single shared branch called “trunk” and eliminates long-living branches. There are two variations based on team size: smaller teams commit directly to the trunk, while larger teams create short-lived feature branches. Frequent integration of smaller feature slices is encouraged to ensure regular merging.

![](/images/trunk-based-development.webp)

Pros:
- Encourages DevOps and unit testing best practices.
- Enhances collaboration and reduces merge conflicts.
- Allows for quick releases.

Cons:
- Requires an experienced team that can slice features appropriately for regular integration.
- Relies on strong continuous integration and continuous delivery/deployment practices to maintain stability.

## **Conclusion**
Between these strategies, there isnt a worst or better one, only a strategy that works best for each team, depending on team size and communication. By following these strategies, teams can be more productive and organized.