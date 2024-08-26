```mermaid
%%{init: {"theme": "base", "themeVariables": {"primaryColor": "#f9f9f9", "edgeLabelBackground":"#ffffff", "tertiaryColor": "#dae8fc", "actorTextColor": "#333", "actorBorderColor": "#333", "lineColor": "#333", "fontSize": "16px"}}}%%
usecaseDiagram
    actor User as "User"
    actor RecyclingProvider as "Recycling Provider"
    actor Admin as "Administrator"
    
    User --> (Buy Recyclable Waste)
    User --> (Sell Recyclable Waste)
    User --> (Find Recycling Providers)
    User --> (View Map & Distance)
    User --> (Manage Social Organizations)
    User --> (Access Government Initiatives)
    User --> (Engage in Second-Hand Item Trading)
    User --> (Access Recycling Tutorials)

    RecyclingProvider --> (Register as Provider)
    RecyclingProvider --> (Manage Provider Profile)
    RecyclingProvider --> (Set Waste Buying Preferences)
    
    Admin --> (Manage Users)
    Admin --> (Monitor Transactions)
    Admin --> (Update Government Initiatives)
    Admin --> (Approve Recycling Providers)
    
    (Find Recycling Providers) --> (Search by Map)
    (Find Recycling Providers) --> (Search by Distance)
    (Find Recycling Providers) --> (TF-IDF Search)
    (Access Recycling Tutorials) --> (Watch Videos)
    (Access Recycling Tutorials) --> (Read Articles)
