```mermaid
graph TB
    Bus[Hydrogen Fuel Cell Electric Transit Bus<br/>R_total = 0.7971]
    
    Bus --> FC[Fuel Cell<br/>R = 0.9626]
    Bus --> H2[Hydrogen Storage & Distribution<br/>R = 0.9848]
    Bus --> BATT[Battery<br/>R = 0.9861]
    Bus --> PWR[Power Conversion & Distribution<br/>R = 0.9801]
    Bus --> ELEC[Electric Propulsion<br/>R = 0.9821]
    Bus --> THERM[Thermal Management<br/>R = 0.9847]
    Bus --> VCU[Vehicle Control & Monitoring<br/>R = 0.9908]
    Bus --> CHAS[Chassis & Mechanical<br/>R = 0.9792]
    Bus --> PAX[Passenger Services<br/>R = 0.9635]
    Bus --> SAFE[Safety & Security<br/>R = 0.9779]
    Bus --> COMM[Communication & Navigation<br/>R = 0.9841]
    
    style Bus fill:#366092,stroke:#333,stroke-width:4px,color:#fff
    style FC fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style H2 fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style BATT fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style PWR fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style ELEC fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style THERM fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style VCU fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style CHAS fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style PAX fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style SAFE fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
    style COMM fill:#4472C4,stroke:#333,stroke-width:2px,color:#fff
