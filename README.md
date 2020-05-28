---
title: 'Learning to learn in Collective Self-adaptive Systems: Automated Reasoning
  for System Design Patterns'
output:
  pdf_document: default
  html_document: 
    keep_md: yes
---

# Dataset


```r
dataset
```

```
##                                                                                                                Title
## 1                                                       Pervasive Self-Learning with Multi-modal Distributed Sensors
## 2                                       Distributed W-Learning: Multi-Policy Optimization in Self-Organizing Systems
## 3                                                     Self-organized Fault-tolerant Routing in Peer-to-Peer Overlays
## 4                                                  Self-organizing Bandwidth Sharing in Priority-Based Medium Access
## 5  Incremental Social Learning Applied to a Decentralized Decision-Making Mechanism: Collective Learning Made Faster
## 6                                                   Simulating Human Single Motor Units Using Self-Organizing Agents
## 7                        Learning to be Different: Heterogeneity and Efficiency in Distributed Smart Camera Networks
## 8                                Self-Organizational Reciprocal Agents for Conflict Avoidance in Allocation Problems
## 9                              A Mutual Influence Detection Algorithm for Systems with Local Performance Measurement
## 10                                    Towards Dynamic Epistemic Learning of Actions in Autonomic Multi-agent Systems
## 11                                                        Cooperative Resource Allocation in Open Systems of Systems
## 12                    Multiagent Reinforcement Social Learning Toward Coordination in Cooperative Multiagent Systems
## 13                                     Efficient and Robust Emergence of Norms Through Heuristic Collective Learning
## 14                                    Reinforcement Learning of Informed Initial Policies for Decentralized Planning
## 15                     Prediction-Based Multi-Agent Reinforcement Learning in Inherently Non-Stationary Environments
## 16                                        A Reinforcement Learning Approach for Interdomain Routing with Link Prices
## 17                                                                    Machine Learning in Disruption-tolerant MANETs
## 18                                                      Mobilized ad-hoc networks: a reinforcement learning approach
## 19                                                                          Autonomous smart routing for network QoS
## 20                                      Decentralized Bayesian Reinforcement Learning for Online Agent Collaboration
## 21              Modeling Assistant s Autonomy Constraints As a Means for Improving Autonomous Assistant-Agent Design
## 22               Adaptivity at Every Layer: A Modular Approach for Evolving Societies of Learning Autonomous Systems
## 23               Bayesian Interaction Shaping: Learning to Influence Strategic Interactions in Mixed Robotic Domains
## 24                                 Resource Abstraction for Reinforcement Learning in Multiagent Congestion Problems
## 25                                    Multiagent Reinforcement Learning and Self-organization in a Network of Agents
## 26                                                                  Batch Reinforcement Learning in a Complex Domain
## 27                                                             Co-evolution of Agent Strategies in N-player Dilemmas
## 28                                                                Self-organisation in an Agent Network via Learning
## 29                                           Self-organization for Coordinating Decentralized Reinforcement Learning
## 30                                                        Adjustable Autonomy in Real-world Multi-agent Environments
## 31                         How Autonomy Oriented Computing (AOC) Tackles a Computationally Hard Optimization Problem
## 32                                                               A Bartering Approach to Improve Multiagent Learning
## 33                                                 Learning Sequences of Actions in Collectives of Autonomous Agents
## 34                                                        Learning and Decision: Making for Intention Reconciliation
## 35                    Continuous Collaboration: A Case Study on the Development of an Adaptive Cyber-physical System
## 36                                               RPLLEARN: Extending an Autonomous Robot Control Language to Perform
## 37                         Coordination Through Mutual Notification in Cooperative Multiagent Reinforcement Learning
## 38                                                          On Topic Selection Strategies in Multi-agent Naming Game
## 39                                         Inter-institutional Social Capital for Self-Organising Nested Enterprises
## 40   Dealing with Unforeseen Situations in the Context of Self-Adaptive Urban Traffic Control: How to Bridge the Gap
## 41                                              Decentralised Progressive Signal Systems for Organic Traffic Control
## 42                                                                                Learning in Open Adaptive Networks
## 43                          A Machine Learning Approach to Performance Prediction of Total Order Broadcast Protocols
## 44                                                    Self-Adaptive Dissemination of Data in Dynamic Sensor Networks
## 45                                 Autonomic Multi-policy Optimization in Pervasive Systems: Overview and Evaluation
## 46                           Self-Organising Zooms for Decentralised Redundancy Management in Visual Sensor Networks
## 47                         Towards Data-centric Control of Sensor Networks through Bayesian Dynamic Linear Modelling
## 48                                   Firefly-Inspired Synchronization for Improved Dynamic Pricing in Online Markets
## 49                                               Decentralized Approaches for Self-adaptation in Agent Organizations
## 50                                    Static Dynamic and Adaptive Heterogeneity in Distributed Smart Camera Networks
## 51                                                               Distributed Cooperation in Wireless Sensor Networks
## 52                                   Prosumers as Aggregators in the DEZENT Context of Regenerative Power Production
## 53                                                   Goal-Aware Team Affiliation in Collectives of Autonomous Robots
## 54                                              Decentralized Collective Learning for Self-Managed Sharing Economies
## 55                                       Constructivist Approach to State Space Adaptation in Reinforcement Learning
## 56                         TSLAM: A Trust-Enabled Self-Learning Agent Model for Service Matching in the Cloud Market
## 57                            Autonomous Management of Energy-Harvesting IoT Nodes Using Deep Reinforcement Learning
## 58                                                                 Reinforcement Learning for Cooperative Overtaking
## 59                                       New quantum-genetic based OLSR protocol (QG-OLSR) for Mobile Ad hoc Network
##                     Application Domain Emergent Behaviour
## 1                                  CPS                 No
## 2                              Traffic                 No
## 3                              Network                Yes
## 4                              Network                Yes
## 5                                Other                Yes
## 6                                Other                 No
## 7                                  CPS                Yes
## 8                                Other                 No
## 9                                  CPS                Yes
## 10                               Other                 No
## 11                                 CPS                 No
## 12                    Cooperative Game                 No
## 13                    Cooperative Game                 No
## 14                                 CPS                 No
## 15                                 CPS                Yes
## 16                             Network                Yes
## 17                             Network                 No
## 18                             Network                 No
## 19                             Network                 No
## 20                                 CPS                 No
## 21                              Market                 No
## 22                                 CPS                 No
## 23                                 CPS                 No
## 24                             Traffic                Yes
## 25 Distributed Task Allocation Problem                 No
## 26                                 CPS                 No
## 27                    Cooperative Game                Yes
## 28 Distributed Task Allocation Problem                 No
## 29 Distributed Task Allocation Problem                Yes
## 30                               Other                 No
## 31                    Cooperative Game                 No
## 32                               Other                 No
## 33                                 CPS                Yes
## 34                              Market                 No
## 35                                 CPS                 No
## 36                                 CPS                 No
## 37                                 CPS                 No
## 38                    Cooperative Game                Yes
## 39                                 CPS                Yes
## 40                             Traffic                 No
## 41                             Traffic                 No
## 42 Distributed Task Allocation Problem                Yes
## 43                             Network                 No
## 44                             Network                Yes
## 45                             Traffic                 No
## 46                                 CPS                 No
## 47                                 CPS                Yes
## 48                              Market                 No
## 49                               Other                 No
## 50                                 CPS                 No
## 51                                 CPS                 No
## 52                                 CPS                Yes
## 53                                 CPS                Yes
## 54                                 CPS                Yes
## 55                             Traffic                 No
## 56                              Market                 No
## 57                                 CPS                Yes
## 58                             Traffic                Yes
## 59                             Network                 No
##    Cooperative (agent level)                           Selfishness
## 1                        Yes             Selfish but collaborative
## 2                        Yes Altruistic locally / Selfish globally
## 3                         No                               Selfish
## 4                         No                               Selfish
## 5                         No                               Selfish
## 6                        Yes                            Altruistic
## 7                         No                               Selfish
## 8                        Yes             Selfish but collaborative
## 9                         No                               Selfish
## 10                        No                               Selfish
## 11                        No                Both versions explored
## 12                        No                Both versions explored
## 13                        No                            Altruistic
## 14                        No                               Selfish
## 15                        No                               Selfish
## 16                        No                               Selfish
## 17                       Yes            Altruistic (collaborative)
## 18                       Yes            Altruistic (collaborative)
## 19                       Yes            Altruistic (collaborative)
## 20                       Yes            Altruistic (collaborative)
## 21                       Yes                               Selfish
## 22                       Yes            Altruistic (collaborative)
## 23                        No Altruistic locally / Selfish globally
## 24                        No                               Selfish
## 25                       Yes             Selfish but collaborative
## 26                       Yes             Selfish but collaborative
## 27                        No                               Selfish
## 28                       Yes             Selfish but collaborative
## 29                        No                               Selfish
## 30                       Yes                            Altruistic
## 31                       Yes                            Altruistic
## 32                       Yes                               Selfish
## 33                        No                               Selfish
## 34                       Yes                               Selfish
## 35                       Yes            Altruistic (collaborative)
## 36                        No                               Selfish
## 37                        No                            Altruistic
## 38                        No                               Selfish
## 39                       Yes                               Selfish
## 40                        No Altruistic locally / Selfish globally
## 41                       Yes            Altruistic (collaborative)
## 42                        No                               Selfish
## 43                        No                               Selfish
## 44                        No                               Selfish
## 45                       Yes                            Altruistic
## 46                       Yes                            Altruistic
## 47                        No                               Selfish
## 48                       Yes             Selfish but collaborative
## 49                       Yes             Selfish but collaborative
## 50                       Yes             Selfish but collaborative
## 51                       Yes             Selfish but collaborative
## 52                        No                               Selfish
## 53                       Yes                            Altruistic
## 54                       Yes                               Tunable
## 55                        No                               Selfish
## 56                       Yes                               Selfish
## 57                        No                               Selfish
## 58                       Yes                            Altruistic
## 59                        No                            Altruistic
##               Autonomy Knowledge Access               Trigger - first
## 1  Restricted Autonomy     Neighborhood No initial knowledge (random)
## 2        Full Autonomy     Neighborhood No initial knowledge (random)
## 3        Full Autonomy          Minimal   From peers and other agents
## 4        Full Autonomy          Limited No initial knowledge (random)
## 5        Full Autonomy          Minimal   From peers and other agents
## 6        Full Autonomy          Limited No initial knowledge (random)
## 7        Full Autonomy          Maximal No initial knowledge (random)
## 8        Full Autonomy          Limited No initial knowledge (random)
## 9        Full Autonomy     Neighborhood No initial knowledge (random)
## 10       Full Autonomy          Maximal No initial knowledge (random)
## 11       Full Autonomy          Tunable     Domain knowledge / humans
## 12       Full Autonomy     Neighborhood No initial knowledge (random)
## 13       Full Autonomy     Neighborhood No initial knowledge (random)
## 14       Full Autonomy          Minimal   From peers and other agents
## 15       Full Autonomy          Minimal     Domain knowledge / humans
## 16       Full Autonomy          Minimal No initial knowledge (random)
## 17       Full Autonomy     Neighborhood No initial knowledge (random)
## 18       Full Autonomy     Neighborhood No initial knowledge (random)
## 19       Full Autonomy     Neighborhood No initial knowledge (random)
## 20       Full Autonomy     Neighborhood No initial knowledge (random)
## 21       Full Autonomy          Minimal                 Not mentioned
## 22       Full Autonomy          Minimal                 Not mentioned
## 23       Full Autonomy          Limited     Domain knowledge / humans
## 24       Full Autonomy          Minimal No initial knowledge (random)
## 25       Full Autonomy          Minimal No initial knowledge (random)
## 26       Full Autonomy          Maximal     Domain knowledge / humans
## 27       Full Autonomy     Neighborhood No initial knowledge (random)
## 28       Full Autonomy     Neighborhood No initial knowledge (random)
## 29       Full Autonomy          Tunable No initial knowledge (random)
## 30 Restricted Autonomy          Maximal     Domain knowledge / humans
## 31       Full Autonomy          Maximal     Domain knowledge / humans
## 32       Full Autonomy          Maximal     Domain knowledge / humans
## 33       Full Autonomy          Minimal No initial knowledge (random)
## 34 Restricted Autonomy          Minimal No initial knowledge (random)
## 35       Full Autonomy          Maximal No initial knowledge (random)
## 36       Full Autonomy          Minimal No initial knowledge (random)
## 37       Full Autonomy          Limited No initial knowledge (random)
## 38       Full Autonomy          Minimal No initial knowledge (random)
## 39       Full Autonomy          Minimal No initial knowledge (random)
## 40       Full Autonomy          Minimal No initial knowledge (random)
## 41       Full Autonomy     Neighborhood                 Not mentioned
## 42       Full Autonomy          Minimal                 Not mentioned
## 43       Full Autonomy          Minimal                 Not mentioned
## 44       Full Autonomy          Limited                 Not mentioned
## 45 Restricted Autonomy     Neighborhood                 Not mentioned
## 46 Restricted Autonomy          Limited No initial knowledge (random)
## 47       Full Autonomy          Minimal No initial knowledge (random)
## 48       Full Autonomy          Maximal No initial knowledge (random)
## 49       Full Autonomy     Neighborhood No initial knowledge (random)
## 50       Full Autonomy     Neighborhood No initial knowledge (random)
## 51       Full Autonomy     Neighborhood                 Not mentioned
## 52 Restricted Autonomy          Tunable                 Not mentioned
## 53       Full Autonomy          Limited No initial knowledge (random)
## 54       Full Autonomy          Minimal     Domain knowledge / humans
## 55       Full Autonomy          Minimal     Domain knowledge / humans
## 56       Full Autonomy          Minimal     Domain knowledge / humans
## 57       Full Autonomy          Minimal     Domain knowledge / humans
## 58       Full Autonomy     Neighborhood     Domain knowledge / humans
## 59       Full Autonomy          Maximal   From peers and other agents
##                    Trigger - update
## 1                          Periodic
## 2                     Not mentioned
## 3                          Periodic
## 4                            Action
## 5                     Not mentioned
## 6                          Periodic
## 7                          Periodic
## 8                          Periodic
## 9                          Periodic
## 10                     Task/Episode
## 11 Learning task threshold achieved
## 12                     Task/Episode
## 13                     Task/Episode
## 14 Learning task threshold achieved
## 15                         Periodic
## 16                           Action
## 17               Social interaction
## 18               Social interaction
## 19                           Action
## 20               Social interaction
## 21                           Action
## 22               Social interaction
## 23                           Action
## 24                    Not mentioned
## 25                           Action
## 26 Learning task threshold achieved
## 27 Learning task threshold achieved
## 28                           Action
## 29                           Action
## 30                     Task/Episode
## 31                           Action
## 32                           Action
## 33                           Action
## 34                           Action
## 35 Learning task threshold achieved
## 36                     Task/Episode
## 37                     Task/Episode
## 38                           Action
## 39 Learning task threshold achieved
## 40 Learning task threshold achieved
## 41 Learning task threshold achieved
## 42                    Not mentioned
## 43                    Not mentioned
## 44                    Not mentioned
## 45                         Periodic
## 46                         Periodic
## 47                         Periodic
## 48                         Periodic
## 49                         Periodic
## 50                     Task/Episode
## 51                         Periodic
## 52                         Periodic
## 53                           Action
## 54                           Action
## 55                     Task/Episode
## 56                         Periodic
## 57                     Task/Episode
## 58                         Periodic
## 59 Learning task threshold achieved
##                                       Technique
## 1                                 Probabilistic
## 2                        Reinforcement Learning
## 3                        Reinforcement Learning
## 4                                   Game Theory
## 5                                    Statistics
## 6                          Evolutionary Process
## 7                        Reinforcement Learning
## 8                        Reinforcement Learning
## 9                        Reinforcement Learning
## 10                                Applied Logic
## 11                          Supervised Learning
## 12                       Reinforcement Learning
## 13                                  Game Theory
## 14                       Reinforcement Learning
## 15                       Reinforcement Learning
## 16                       Reinforcement Learning
## 17                                Probabilistic
## 18                       Reinforcement Learning
## 19                       Reinforcement Learning
## 20                       Reinforcement Learning
## 21                          Supervised Learning
## 22                       Reinforcement Learning
## 23                                Probabilistic
## 24                       Reinforcement Learning
## 25                       Reinforcement Learning
## 26                       Reinforcement Learning
## 27                                  Game Theory
## 28                       Reinforcement Learning
## 29                       Reinforcement Learning
## 30                       Reinforcement Learning
## 31                                  Game Theory
## 32                          Supervised Learning
## 33                       Reinforcement Learning
## 34                       Reinforcement Learning
## 35                       Reinforcement Learning
## 36                                   Statistics
## 37                       Reinforcement Learning
## 38                                  Game Theory
## 39                          Supervised Learning
## 40                       Reinforcement Learning
## 41                       Reinforcement Learning
## 42                       Reinforcement Learning
## 43                          Supervised Learning
## 44                       Reinforcement Learning
## 45                       Reinforcement Learning
## 46                       Reinforcement Learning
## 47                                Probabilistic
## 48                                 Swarm System
## 49                       Reinforcement Learning
## 50                                 Swarm System
## 51       Game Theory and Reinforcement Learning
## 52                       Reinforcement Learning
## 53                       Reinforcement Learning
## 54                             Gradiend Descend
## 55                       Reinforcement Learning
## 56                          Supervised Learning
## 57                       Reinforcement Learning
## 58                       Reinforcement Learning
## 59 Genetic Algorithm and Reinforcement Learning
```


# Clustering Analysis

The notion of similarity between papers refersto similarity between their attributes (see dataset). Since the attributes identified by our classification are categorical, we adopt the Gower Distance measure.


```r
gower.dist <- daisy(x, metric = c("gower"))
```

HAC  starts  by  treating  each  observation  (i.e.,paper)  as  a  separate  cluster.  Then,  it  repeatedlyidentifies and merge the two most similar clusters.


```r
aggl.clust.c <- hclust(gower.dist, method = "complete")
plot(aggl.clust.c,cex = 0.7)
```

<img src="figure/unnamed-chunk-3-1.png" title="plot of chunk unnamed-chunk-3" alt="plot of chunk unnamed-chunk-3" style="display: block; margin: auto;" />


There are two methods allowing establishing evaluation  criteria for the number ofclusters K to adopt: silhouette values and the bootstrap method.

Silhouette Analysis:


```r
ggplot(data = data.frame(t(cstats.table(gower.dist, aggl.clust.c, 10))), 
       aes(x=cluster.number, y=avg.silwidth)) + 
  geom_point(size=1.5)+
  geom_line(size=0.5)+
  scale_x_continuous(breaks = scales::pretty_breaks(n = 10), limits=c(2, 10)) +
  scale_y_continuous(breaks = scales::pretty_breaks(n = 10)) +
  ggtitle("") +
  labs(x = "K", y = "Average silhouette width") +
  theme_minimal(base_size = 15) +
  geom_hline(yintercept=0.18, linetype="dashed", 
                color = "red", size=1)
```

<img src="figure/unnamed-chunk-4-1.png" title="plot of chunk unnamed-chunk-4" alt="plot of chunk unnamed-chunk-4" style="display: block; margin: auto;" />


Silhouette Analysis Bootstrap of Clusters and Visualization:

* 2 CLUSTERS:


```r
kchoice<-2
invisible(capture.output(cboot.hclust <- clusterboot(gower.dist,distances=TRUE,clustermethod=hclustCBI, k=kchoice,method="complete",seed="123456789")))
cboot.hclust$bootmean  
```

```
## [1] 0.8423149 0.7770231
```

```r
cboot.hclust$bootbrd 
```

```
## [1] 0 2
```


```r
dendro <- as.dendrogram(aggl.clust.c)
dendro.col <- dendro %>%
 set("branches_k_color", k = 2, value =   c("#2E9FDF","red")) %>% 
  set("branches_lwd", 1) %>%
  set("labels_colors", k = 2, value =   c("#2E9FDF","red")) %>% 
  set("labels_cex", 1)
circlize_dendrogram(dendro.col)
```

<img src="figure/unnamed-chunk-6-1.png" title="plot of chunk unnamed-chunk-6" alt="plot of chunk unnamed-chunk-6" style="display: block; margin: auto;" />

* 3 CLUSTERS:


```r
kchoice<-3
invisible(capture.output(cboot.hclust <- clusterboot(gower.dist,distances=TRUE,clustermethod=hclustCBI, k=kchoice,method="complete",seed="123456789")))
cboot.hclust$bootmean  
```

```
## [1] 0.8269758 0.8038819 0.4952221
```

```r
cboot.hclust$bootbrd 
```

```
## [1]  1  2 57
```


```r
dendro <- as.dendrogram(aggl.clust.c)
dendro.col <- dendro %>%
 set("branches_k_color", k = 3, value =   c("#2E9FDF", "red","#E7B800")) %>% 
set("branches_lwd", 1) %>%
set("labels_colors", k = 3, value =   c("#2E9FDF", "red","#E7B800")) %>% 
set("labels_cex", 1)
circlize_dendrogram(dendro.col)
```

<img src="figure/unnamed-chunk-8-1.png" title="plot of chunk unnamed-chunk-8" alt="plot of chunk unnamed-chunk-8" style="display: block; margin: auto;" />

* 4 CLUSTERS:


```r
kchoice<-4
invisible(capture.output(cboot.hclust <- clusterboot(gower.dist,distances=TRUE,clustermethod=hclustCBI, k=kchoice,method="complete",seed="123456789")))
cboot.hclust$bootmean  
```

```
## [1] 0.8441289 0.8300746 0.5662892 0.4727753
```

```r
cboot.hclust$bootbrd 
```

```
## [1]  1  4 49 64
```


```r
dendro <- as.dendrogram(aggl.clust.c)
dendro.col <- dendro %>%
  set("branches_k_color", k = 4, value =   c("#2E9FDF","red","#E7B800","darkgreen")) %>% 
  set("branches_lwd", 1) %>%
  set("labels_colors", k = 4, value =   c("#2E9FDF","red","#E7B800","darkgreen")) %>% 
  set("labels_cex", 1)
circlize_dendrogram(dendro.col)
```

<img src="figure/unnamed-chunk-10-1.png" title="plot of chunk unnamed-chunk-10" alt="plot of chunk unnamed-chunk-10" style="display: block; margin: auto;" />

* 9 CLUSTERS:


```r
kchoice<-9
invisible(capture.output(cboot.hclust <- clusterboot(gower.dist,distances=TRUE,clustermethod=hclustCBI, k=kchoice,method="complete",seed="123456789")))
cboot.hclust$bootmean  
```

```
## [1] 0.6946536 0.5451034 0.5109907 0.6680000 0.7800000 0.6060833 0.4335839
## [8] 0.4879693 0.3661667
```

```r
cboot.hclust$bootbrd 
```

```
## [1] 21 53 64 35 28 46 72 67 86
```


```r
dendro <- as.dendrogram(aggl.clust.c)
dendro.col <- dendro %>%
  set("branches_lwd", 1) %>%
  set("labels_colors", k = 9, value=c("#2E9FDF","red","#E7B800","darkgreen", "blue","darkorange","black","gray","purple")) %>% 
  set("labels_cex", 1)
circlize_dendrogram(dendro.col)
```

<img src="figure/unnamed-chunk-12-1.png" title="plot of chunk unnamed-chunk-12" alt="plot of chunk unnamed-chunk-12" style="display: block; margin: auto;" />
