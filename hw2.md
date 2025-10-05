graph TD
    Start((Start)) --> T1[任務1 (1天)];
    T1 --> T2[任務2 (4天)];
    T1 --> T3[任務3 (17天)];
    T2 --> T4[任務4 (70天)];
    T3 --> T5[任務5 (10天)];
    T4 --> T6[任務6 (30天)];
    T5 --> T7[任務7 (25天)];
    T5 --> T8[任務8 (20天)];
    T6 --> T9[任務9 (25天)];
    T7 --> T10[任務10 (20天)];
    T8 --> T10;
    T9 --> T11[任務11 (25天)];
    T10 --> T11;
    T11 --> End((End));

    style Start fill:#fff,stroke:#333,stroke-width:2px
    style End fill:#fff,stroke:#333,stroke-width:2px
