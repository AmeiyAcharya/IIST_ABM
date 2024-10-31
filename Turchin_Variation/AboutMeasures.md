### Algebraic Connectivity (AC)
**Description in Context:**
In this simulation of warring villages, algebraic connectivity (AC) measures the overall cohesion and robustness of the network formed by the villages. Specifically, it assesses how tightly interconnected the network of villages is after various wars and the formation of polities. The AC is derived from the Laplacian matrix of the graph representing the villages and their connections, with the second smallest eigenvalue being the AC. Higher AC indicates a more robust and resilient network, implying that the villages are well connected and can withstand the removal of certain connections without fragmenting.

**Interpretation in Context:**
In practical terms, if the AC of the village network is high, it suggests that even if some villages (nodes) or alliances (edges) are destroyed during wars, the overall network remains intact. This resilience is crucial for maintaining stable polities and ensuring the continuity of resource flow and communication between villages. For instance, a high AC would imply that the network can sustain its structure and functions despite the chaos of wars, indicating strong political and social stability within the emergent hierarchies.

### Network Criticality (NC)
**Description in Context:**
Network criticality (NC) in the context of warring villages refers to the vulnerability of the village network to the removal of key villages or connections. It quantifies how the overall connectivity and function of the network degrade as nodes (villages) or edges (alliances) are removed. NC can be calculated by observing changes in metrics such as the largest connected component size or the average path length as nodes are progressively removed based on certain criteria, such as resource levels or betweenness centrality.

**Interpretation in Context:**
A high network criticality indicates that the village network is highly dependent on specific villages or alliances. This means that the removal or destruction of a few key villages could significantly disrupt the network, leading to fragmentation and the collapse of polities. For example, if a central village with high resource levels and strategic alliances is attacked and defeated, the entire network might suffer, showing high criticality. This measure helps identify critical nodes that need protection to maintain the stability and resilience of the village network.

### Effective Graph Conductance (EGC)
**Description in Context:**
Effective graph conductance (EGC) measures the efficiency of resource and information flow through the network of villages. It is calculated using the concept of electrical conductance, where each village and its connections are akin to a network of resistors. The EGC is determined by assessing the effective resistance between pairs of villages, with lower resistance indicating higher conductance and thus more efficient flow.

**Interpretation in Context:**
In the village network, a high EGC signifies that resources and information can be easily and efficiently distributed across the villages. This is crucial during wars and the formation of polities, as it ensures that villages can support each other and maintain stability. For instance, a village network with high EGC would be able to quickly reallocate resources from richer villages to those in need, enhancing the overall resilience and coherence of the polities formed. Conversely, low EGC indicates potential bottlenecks and inefficiencies, making the network more susceptible to disruptions.

### Natural Connectivity (NaC)
**Description in Context:**
Natural connectivity (NaC) quantifies the robustness and redundancy of the village network by averaging the exponential of the eigenvalues of the adjacency matrix. It reflects the overall stability of the network by considering all possible paths and connections. NaC can be seen as a measure of how many alternative routes and connections exist within the network, providing insights into its resilience.

**Interpretation in Context:**
In the context of warring villages, a high natural connectivity means that the network has many alternative paths and connections, ensuring that the failure or destruction of a few villages or alliances does not critically disrupt the network. This redundancy is vital for maintaining communication and resource flow, especially during conflicts. For instance, if a war destroys a few key alliances, a high NaC would mean that other paths and connections can compensate, preventing the network from falling apart and maintaining the integrity of the polities formed.

### Variance of Node Betweenness
**Description in Context:**
The variance of node betweenness in the village network measures the disparity in the importance of villages in terms of their role as bridges or intermediaries in communication and resource flow. Betweenness centrality for a village is the number of shortest paths that pass through it. The variance of these values across all villages provides insights into the distribution of central roles within the network.

**Interpretation in Context:**
A high variance in node betweenness indicates that some villages play significantly more critical roles as intermediaries than others. This could mean that certain villages act as major hubs, controlling resource distribution and communication. In the context of warring villages, these central villages are crucial for maintaining network stability and would be primary targets in conflicts. Conversely, a low variance suggests a more evenly distributed network, where no single village dominates the flow, indicating a more resilient and decentralized network structure.

### Variance of Link Betweenness
**Description in Context:**
The variance of link betweenness measures the disparity in the importance of connections (alliances) between villages in terms of their role in facilitating shortest paths. Betweenness centrality for a link is the number of shortest paths that pass through it. The variance of these values across all links provides insights into the distribution of critical connections within the network.

**Interpretation in Context:**
In the village network, a high variance in link betweenness suggests that certain alliances are crucial for maintaining the network’s connectivity. These critical alliances, if disrupted, could significantly impact the flow of resources and information. In the context of warring villages, identifying these high-betweenness links can help in understanding which alliances are vital for the stability of polities and should be protected or targeted during conflicts. A low variance indicates a more evenly distributed network, where no single alliance is disproportionately important, enhancing overall network resilience.

### Mean and Variance of Number of Edge Disjoint Paths
**Description in Context:**
Edge disjoint paths are multiple paths between two villages that do not share any common edges. The mean number of edge disjoint paths across all village pairs gives an average measure of redundancy in connections, while the variance indicates the spread of this redundancy. These metrics are crucial for assessing the fault tolerance and robustness of the network.

**Interpretation in Context:**
In the village network, a high mean number of edge disjoint paths indicates that there are multiple independent routes for resource flow between villages, enhancing network resilience. A high variance suggests that some village pairs have significantly more alternative routes than others, highlighting potential vulnerabilities. For instance, during conflicts, village pairs with fewer edge disjoint paths are more vulnerable to isolation if specific alliances are disrupted. Understanding these metrics helps in strategic planning to ensure that critical connections are maintained and redundancy is maximized.

### Mean and Variance of Number of Node Disjoint Paths
**Description in Context:**
Node disjoint paths are multiple paths between two villages that do not share any common intermediate villages. The mean number of node disjoint paths across all village pairs provides an average measure of redundancy in terms of independent pathways, while the variance indicates the spread of this redundancy.

**Interpretation in Context:**
A high mean number of node disjoint paths in the village network indicates that there are multiple independent routes for communication and resource flow, enhancing fault tolerance. High variance suggests that some village pairs have significantly more alternative routes than others, pointing to uneven distribution of redundancy. In the context of warring villages, pairs with fewer node disjoint paths are more susceptible to being cut off if certain villages are attacked. Ensuring a higher number of node disjoint paths enhances the overall resilience and stability of the network, preventing isolation during conflicts.

### Trophic Levels of Vertices
**Description in Context:**
In the village network, trophic levels of vertices represent the hierarchical levels based on resource acquisition and dependency. Basal villages, which gather resources directly from the environment, are at the lowest trophic level. Villages that depend on resources from other villages are placed at higher trophic levels. The trophic level calculation starts with basal villages assigned a level of 1, and other villages' levels are computed based on the average level of their predecessors plus one.

**Interpretation in Context:**
Trophic levels provide insights into the hierarchical structure of the village network. Villages at higher trophic levels depend on resources from lower-level villages, indicating a dependency chain. In the context of warring villages, understanding trophic levels helps identify key resource providers and consumers, revealing the flow of resources and the potential impact of conflicts on the network's stability. Villages at lower trophic levels are crucial for the survival of higher-level villages, making them strategic targets or important nodes to protect.

### Trophic Coherence
**Description in Context:**
Trophic coherence measures the uniformity of trophic levels within the village network. It is calculated as the standard deviation of the trophic levels' distribution or through a coherence index that quantifies deviations from expected trophic positions. High trophic coherence indicates a well-organized, hierarchical network, while low coherence suggests complex or less structured interactions.

**Interpretation in Context:**
In the village network, high trophic coherence means that the hierarchical structure is well-defined, with clear levels of resource acquisition and dependency. This stability is crucial during conflicts, as it ensures predictable resource flow and supports effective governance within polities. Low trophic coherence indicates a more complex and less stable network, where resource flow is less predictable, and hierarchies are less clear. Understanding trophic coherence helps in strategizing resource distribution and maintaining network stability during conflicts.

### Cycle Basis
**Description in Context:**
A cycle basis of the village network is a minimal set of cycles from which all other cycles can be derived. It is calculated using algorithms such as Horton's algorithm, which involves finding fundamental cycles based on a spanning tree of the graph. The

 cycle basis provides insights into the cyclic structure and redundancy of the network.

**Interpretation in Context:**
In the context of warring villages, the cycle basis reveals the underlying cyclic structure, indicating potential redundancies and alternative routes. Understanding the cycle basis helps identify robust paths that can maintain connectivity even if certain connections are disrupted. This knowledge is crucial for strategic planning during conflicts, as it highlights critical cycles that support network resilience and stability. A well-connected cycle basis suggests a resilient network with multiple pathways for resource flow and communication.

### Assortativity Coefficient
**Description in Context:**
The assortativity coefficient measures the tendency of villages to connect with others that are similar in terms of certain attributes, such as resources or hierarchy. It is calculated using the Pearson correlation coefficient between the attributes of connected nodes. Positive values indicate assortative mixing (similar nodes connect), while negative values indicate disassortative mixing (dissimilar nodes connect).

**Interpretation in Context:**
In the village network, a high positive assortativity coefficient suggests that villages with similar resource levels or hierarchical positions tend to form alliances, leading to homogenous clusters. This can enhance internal stability within these clusters but may also create divisions between different clusters. Negative assortativity indicates that villages form connections with others that are different in resources or hierarchy, promoting diversity and potentially enhancing overall network resilience. Understanding assortativity helps in analyzing the formation of alliances and the stability of polities within the network.

### Influence Centrality
**Description in Context:**
Influence centrality measures a village's ability to influence the dynamics and resource flow within the network. It is calculated by considering both the direct and indirect influence a village has on others, often using iterative algorithms that account for the influence of neighbors and their neighbors. This centrality metric reflects the overall impact of a village on the network's behavior.

**Interpretation in Context:**
In the context of warring villages, high influence centrality indicates that a village plays a crucial role in shaping the network's dynamics, affecting resource distribution, alliances, and conflict outcomes. Such villages are key players in the formation and stability of polities, and their actions can significantly impact the network. Identifying villages with high influence centrality helps in understanding power dynamics and potential leverage points within the network, guiding strategic decisions during conflicts and resource management.

### Democracy Coefficient
**Description in Context:**
The democracy coefficient measures the overall feedback and equality in resource distribution within the village network. It is calculated by assessing the uniformity of resource distribution and the extent to which villages share resources and influence. A high democracy coefficient indicates a more egalitarian network, while a low coefficient suggests centralized control.

**Interpretation in Context:**
In the village network, a high democracy coefficient means that resources and influence are distributed more evenly among the villages, promoting stability and cooperation. This egalitarian structure can enhance the resilience of polities and reduce the likelihood of conflicts arising from resource inequality. Conversely, a low democracy coefficient indicates centralized control, where a few villages dominate resource distribution and influence, potentially leading to instability and conflicts. Understanding the democracy coefficient helps in designing strategies to promote equitable resource distribution and maintain network stability.

### Global Reaching Centrality
**Description in Context:**
Global reaching centrality measures the extent to which a village can reach all other villages in the network, either directly or indirectly. It is calculated by considering the proportion of nodes that a given node can influence within a specified number of steps. This centrality metric provides insights into the global influence of a village within the network.

**Interpretation in Context:**
In the village network, high global reaching centrality indicates that a village has a broad influence, reaching most or all other villages either directly or through a few intermediaries. Such villages are crucial for maintaining network cohesion and stability, especially during conflicts. They can facilitate resource distribution and communication across the network, supporting the formation and maintenance of polities. Villages with high global reaching centrality are strategic points of control, and their protection or targeting can significantly impact the network's dynamics.

### Local Reaching Centrality
**Description in Context:**
Local reaching centrality measures the influence of a village within its immediate neighborhood. It is calculated by considering the proportion of nearby villages that a given village can reach directly within a certain number of steps. This metric focuses on the local influence and impact of a village.

**Interpretation in Context:**
In the context of warring villages, high local reaching centrality means that a village has a strong influence within its local community, affecting resource distribution and alliances in its vicinity. Such villages act as local leaders or hubs, playing a crucial role in the stability and dynamics of their immediate surroundings. Understanding local reaching centrality helps in identifying key local influencers that can support or disrupt the network during conflicts, guiding strategic decisions for maintaining local stability and resource flow.

### Maximum Betweenness Centrality
**Description in Context:**
Maximum betweenness centrality identifies the village that serves as the most crucial bridge within the network, facilitating the flow of resources and communication between different parts. It is calculated by determining the number of shortest paths that pass through each village and selecting the village with the highest betweenness centrality score.

**Interpretation in Context:**
In the village network, the village with maximum betweenness centrality is a critical node that significantly influences the overall connectivity and stability. Its removal or destruction during conflicts can lead to severe disruptions in resource flow and communication, potentially fragmenting the network. Identifying this key village helps in understanding the network's vulnerability and planning strategies to protect or exploit this crucial node during conflicts. The maximum betweenness centrality highlights the importance of certain villages in maintaining the network's integrity.

### Modularity
**Description in Context:**
Modularity measures the strength of division of the village network into distinct communities or polities. It is calculated by comparing the density of connections within communities to the density of connections between communities. High modularity indicates well-defined communities with strong internal connections and weaker external links.

**Interpretation in Context:**
In the context of warring villages, high modularity suggests that villages form well-defined polities with strong internal alliances and fewer connections to other polities. This structure can enhance internal stability and cooperation within polities but may also lead to isolation and conflict between different polities. Understanding modularity helps in analyzing the formation and stability of polities, guiding strategies to promote cohesion within communities and manage interactions between them. High modularity indicates a network with clear community structures, while low modularity suggests a more integrated and less polarized network.

### Edge Distribution Across Levels
**Description in Context:**
Edge distribution across levels in the village network measures how connections (alliances) are distributed among different hierarchical levels. It involves categorizing edges based on the hierarchical level of the villages they connect and computing the frequency distribution of these edges.

**Interpretation in Context:**
Understanding edge distribution across levels helps in analyzing the interaction patterns between different hierarchical levels within the village network. In the context of warring villages, this measure reveals how resources and information flow between different levels of the hierarchy, indicating whether the network is centralized or distributed. A balanced distribution across levels suggests a well-integrated network with multiple pathways for resource flow, enhancing overall resilience. Conversely, skewed distribution indicates potential bottlenecks and vulnerabilities, guiding strategies to improve network stability and resource distribution.

## Measures

### Node-Level Measures

1. **Variance of Node Betweenness**: Measures the disparity in the importance of villages as intermediaries in communication and resource flow.
2. **Trophic Levels of Vertices**: Represents the hierarchical levels based on resource acquisition and dependency.
3. **Influence Centrality**: Measures a village's ability to influence the dynamics and resource flow within the network.
4. **Local Reaching Centrality**: Measures the influence of a village within its immediate neighborhood.
5. **Maximum Betweenness Centrality**: Identifies the village that serves as the most crucial bridge within the network.
6. **Degree**: Number of connections a village has.
7. **Clustering Coefficient**: Measures how interconnected a village’s neighbors are.

### Edge-Level Measures

1. **Variance of Link Betweenness**: Measures the disparity in the importance of connections (alliances) between villages.
2. **Mean and Variance of Number of Edge Disjoint Paths**: Measures the redundancy of independent routes between village pairs that do not share any common edges.
3. **Edge Distribution Across Levels**: Measures how connections are distributed among different hierarchical levels.

### Graph-Level Measures

1. **Algebraic Connectivity (AC)**: Measures the overall cohesion and robustness of the network.
2. **Network Criticality (NC)**: Quantifies the vulnerability of the network to the removal of key villages or connections.
3. **Effective Graph Conductance (EGC)**: Measures the efficiency of resource and information flow through the network.
4. **Natural Connectivity (NaC)**: Quantifies the robustness and redundancy of the network by considering all possible paths and connections.
5. **Mean and Variance of Number of Node Disjoint Paths**: Measures the redundancy of independent routes between village pairs that do not share any common intermediate villages.
6. **Trophic Coherence**: Measures the uniformity of trophic levels within the network.
7. **Cycle Basis**: Reveals the underlying cyclic structure and redundancy of the network.
8. **Assortativity Coefficient**: Measures the tendency of villages to connect with others that are similar in terms of certain attributes.
9. **Democracy Coefficient**: Measures the overall feedback and equality in resource distribution within the network.
10. **Global Reaching Centrality**: Measures the extent to which a village can reach all other villages in the network.
11. **Modularity**: Measures the strength of division of the network into distinct communities or polities.