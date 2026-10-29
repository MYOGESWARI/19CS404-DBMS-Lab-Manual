# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:

<img width="1100" height="662" alt="image" src="https://github.com/user-attachments/assets/5349ee3a-0f2e-4b31-a18d-f0d28fd1672f" />


### Entities and Attributes

<img width="1105" height="372" alt="image" src="https://github.com/user-attachments/assets/d900717d-b1e4-4fb2-a812-f3e0209d4df9" />


### Relationships and Constraints

<img width="1107" height="377" alt="image" src="https://github.com/user-attachments/assets/c394068f-db0b-462e-8384-e91ec4f30099" />



### Assumptions

1.Each session involves exactly one trainer and one member.
2.Programs are predefined (Yoga, Zumba, Weight Training, etc.).
3.Payments are only for membership or session bookings.


# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:

<img width="1056" height="702" alt="image" src="https://github.com/user-attachments/assets/bfb91114-1b9d-4920-a29d-d6c42b1e96ec" />


### Entities and Attributes

<img width="928" height="305" alt="image" src="https://github.com/user-attachments/assets/75e5fe21-36d0-4612-98ee-4045f7851823" />


### Relationships and Constraints

<img width="762" height="175" alt="image" src="https://github.com/user-attachments/assets/b127f41b-8218-4d1b-9fb9-42e82bb76691" />



### Assumptions

1.Books can be borrowed multiple times by different Members.
2.Each Event happens in one Room at a specific time.
3.A Speaker can participate in multiple Events.

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:

<img width="1102" height="545" alt="image" src="https://github.com/user-attachments/assets/02fc4266-dd32-47ae-925d-a709418bdbb0" />


### Entities and Attributes

<img width="927" height="266" alt="image" src="https://github.com/user-attachments/assets/9f6e1d9e-2d2f-414b-9498-fc408f52f130" />


### Relationships and Constraints

<img width="802" height="205" alt="image" src="https://github.com/user-attachments/assets/95ec4b9c-91e6-4436-9835-bf34b8d5fc24" />


### Assumptions

1.One reservation uses one table and one waiter.
2.Bill is generated automatically after service.
3.Customer details stored for every reservation.

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
