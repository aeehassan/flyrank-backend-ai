## Finalized Project Plan

1. Outline the presentation slides; augmentation
2. Finalize the content scope; automation - I'd only cross-check its output
3. Define design color system; augmentation - AI drafts whilst I verify taste and appeal
4. Design the diagrams; automation
5. Build the deck, however AI gives me layout ideas
6. Proofread; automation
7. Review and polish slides
8. Rehearse and review with AI

### #1
| # | Slide | Badge | Visual | Time | Key takeaway |
|---|---|---|---|---|---|
| 1 | Machine Learning Algorithms: Which algorithm do I pick? | none | Bold title text on a blank background | 30s | There are many algorithms, and today you’ll learn six of them. |
| 2 | The 3 families | all three | Three color-coded blocks, each listing its algorithm names | 50s | Algorithms are grouped by how they learn: from labeled examples, from patterns in unlabeled data, or from trial and error. |
| 3 | Linear Regression | Supervised | Scatter plot with fitted line | 50s | It finds the straight line that best fits the data, so it can predict a number. |
| 4 | Decision Trees | Supervised | Small branching tree | 50s | It makes a decision by asking a series of yes/no questions. |
| 5 | k-Nearest Neighbors | Supervised | Dots with neighbors circled | 50s | A new point takes the label of the points closest to it. |
| 6 | K-Means Clustering | Unsupervised | Unlabeled dots grouped into clusters | 50s | It groups similar data points together without being told the groups. |
| 7 | PCA | Unsupervised | 3D cloud flattened to 2D | 50s | It shrinks many features into fewer ones while keeping the most important information. |
| 8 | Q-Learning | Reinforcement | Grid world with agent and rewards | 50s | An agent learns the best actions by trying things and collecting rewards. |
| 9 | So, which one do I pick? | all three | Three color-coded columns, one-line use case per algorithm | 50s | The best algorithm depends on your data and your goal. |

Timing check: 30 + 50 + (6 × 50) + 50 = 430 seconds = 7:10.

Slides 3-8 layout (unchanged): family badge, algorithm name, one diagram, “Use it for:” label.

### #2 
Slide text

Slide 1: Title (no badge)

Title: Machine Learning Algorithms: Which algorithm do I pick?

Slide 2: The 3 Families (all three badges)

Title: The 3 Families
Block 1 (Supervised): Learns from labeled examples, followed by Linear Regression, Decision Trees, k-Nearest Neighbors
Block 2 (Unsupervised): Finds patterns in unlabeled data, followed by K-Means Clustering, PCA
Block 3 (Reinforcement): Learns by trial and error, followed by Q-Learning

Slide 3: Linear Regression (Supervised badge)

Title: Linear Regression
Line: Finds the straight line that best fits the data to predict a number.
Use it for: Predicting house prices
Visual: scatter plot with fitted line

Slide 4: Decision Trees (Supervised badge)

Title: Decision Trees
Line: Makes a decision by asking a series of yes/no questions.
Use it for: Approving or rejecting loan applications
Visual: small branching tree

Slide 5: k-Nearest Neighbors (Supervised badge)

Title: k-Nearest Neighbors
Line: Gives a new point the label of the points closest to it.
Use it for: Recommending movies based on similar users
Visual: dots with neighbors circled

Slide 6: K-Means Clustering (Unsupervised badge)

Title: K-Means Clustering
Line: Groups similar data points together without being told the groups.
Use it for: Grouping customers by shopping behavior
Visual: unlabeled dots grouped into clusters

Slide 7: PCA (Unsupervised badge)

Title: PCA (Principal Component Analysis)
Line: Shrinks many features into fewer ones while keeping the most important information.
Use it for: Simplifying data with many features so it is easier to plot
Visual: 3D cloud flattened to 2D

Slide 8: Q-Learning (Reinforcement badge)

Title: Q-Learning
Line: Learns the best actions by trying things and collecting rewards.
Use it for: Training game-playing AI and robots
Visual: grid world with agent and rewards

Slide 9: Recap (all three badges)

Title: So, which one do I pick?
Supervised column:
Linear Regression: Predicting house prices
Decision Trees: Approving or rejecting loan applications
k-Nearest Neighbors: Recommending movies based on similar users
Unsupervised column:
K-Means Clustering: Grouping customers by shopping behavior
PCA: Simplifying data with many features
Reinforcement column:
Q-Learning: Training game-playing AI and robots
Bottom line: The best choice depends on your data and your goal.

### #3

#### 1. Neutral colors

| Role | Color | Hex |
|---|---|---|
| Background | Soft white | `#FAFAF8` |
| Main text (titles, body) | Near-black | `#1F2933` |
| Secondary text, neutral diagram dots and lines | Warm stone | `#57534E` |

#### 2. Family colors

| Family | Main color | Light tint (block backgrounds) |
|---|---|---|
| Supervised | Blue `#2563EB` | `#DBEAFE` |
| Unsupervised | Teal `#0F766E` | `#CCFBF1` |
| Reinforcement | Burnt orange `#C2410C` | `#FFEDD5` |

- **Main color** is for badges, family-colored text, and the key parts of a diagram.
- **Tint** is for the big blocks and columns on slides 2 and 9.
- **Readability:** White text on all three main colors is easy to read. Warm stone on the soft white background is also clear from the back of a room.

#### 3. Fonts

| Use | Font | Size |
|---|---|---|
| Slide titles | Poppins Bold | 40 pt |
| One-line explanation | Inter Regular | 24 pt |
| "Use it for:" label | Inter Bold in the family color, followed by the use case in Inter Regular | 22 pt |
| Badge text | Inter Bold | 14 pt |
| Secondary text | Inter Regular in Warm stone | 18 pt minimum |

Install both fonts on your laptop before building the deck.

#### 4. Badge style

- **Shape:** Rounded pill
- **Fill:** The family's main color
- **Text:** White, bold, sentence case: "Supervised", "Unsupervised", "Reinforcement"
- **Position:** Top-left corner of every slide except slide 1, always the same spot and size
- **Slides 2 and 9:** All three badges appear, each on top of its own block or column

#### 5. Color use per slide

- **Slide 1:** Soft white background and near-black title. The thin three-color bar under the title is optional.
- **Slides 2 and 9:** Three tinted blocks or columns, each with its main-color badge on top.
- **Slides 3-8:** Soft white background. The family color appears only in the badge, the key parts of the diagram, and the "Use it for:" label.
- **Diagrams:** Warm stone for background elements such as unlabeled dots, and the family color for what the eye should find.
