```mermaid
classDiagram

class Categories 
{
    id: number;
    name: string; // 64
    color: string; // 7
}

class Comments
{
    id: number;
    createdAt: Date;
    
    personName: string; // 64
    personEmoji: string; // 64
    personColor: string; // 7
    categoryId: number; 
    message: string; // 1024
}

```