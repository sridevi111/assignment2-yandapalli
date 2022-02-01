# assignment2-yandapalli
# Sridevi Yandapalli
###### Rajamundry
> **Times Square** is a major commercial intersection, tourist destination, entertainment center, and neighborhood in midtown Manhattan in New York City. *It is formed by the junction of Broadway, Seventh Avenue and 42nd Street.* Together with adjacent Duffy Square, Times Square is a bowtie-shaped space five blocks long between 42nd and 47th Streets.

---

## Directions for traveling to food location from the airport

Airport that is closest to my food location is *Rajiv Gandhi Intenational Airport*.<br>
Below are the step by step directions for traveling to my food location from the airport
1. After coming out from the airport take a cab to Complex.
2. From Complex take a bus to Rajahmahendravaram complex bus stop.
3. From complex bus stop in Rajahmahendravaram, take a cab to Tilak Road which is 10 minutes away from complex.
4. From Tilak Road take right and then we can see Big Bazar, from there go straight and we get my Favourit food location which is Rajamundry.

## Best food items in Rajamundry

List of specific foods items from your location that i would recommend for others in Rajamundry 
- Blue Lagoon Mojito
- Chicken Manchuria
- Main course
    - Dum Biryani
    - Prawn Biryani
- Deserts
    - Cheese Cake
    - Walnut Brownie with Ice Cream

---

[This is my AboutMe Link](https://github.com/sridevi111/assignment2-yandapalli/blob/main/AboutMe.md)

---

# Table For Sports

Creating a table with 4 sports that i would recommend someone to try. It includes details about the Sport, Location and the amount of money needed for the personal equipment.
| Sport | Location | Amount in $|
| --- | --- | ---: |
| American Foot Ball | Maryville | 50 |
| Golf | Poland | 160 |
| Tennis | Kansas | 40 |
| cricket | India | 70 |

---

# Life quotes

> “The greatest glory in living lies not in never falling, but in rising every time we fall.”
>> *Nelson Mandela*

> “If life were predictable it would cease to be life, and be without flavor.”
>> *Eleanor Roosevelt*

---

# Code Fencing

> Graph Traversal refers to the process of visiting (checking and/or updating) each vertex in a graph. Such traversals are classified by the order in which the vertices are visited. Tree traversal is a special case of graph traversal.

[Link to source](https://en.wikipedia.org/wiki/Graph_traversal)

```
vector<vector<int>> adj; // graph represented as an adjacency list
int n; // number of vertices

vector<bool> visited;

void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}

```
[Link to source code - Depth First Search](https://cp-algorithms.com/graph/depth-first-search.html)
