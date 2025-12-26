### Here We go on a Researching about 3d printers
Today, I conducted detailed research on 3D printing technology to understand how different types of 3D printers work. I learned that 3D printers create objects by depositing material layer by layer using a process called additive manufacturing. The most commonly used method in desktop 3D printers is FDM (Fused Deposition Modeling), where plastic filament is heated and extruded through a nozzle.

During my research, I studied different motion systems used in 3D printers, such as Cartesian, Delta, and CoreXY. Cartesian printers move along X, Y, and Z axes using separate motors, which makes them easy to understand but slower at high speeds. Delta printers are faster but more complex and difficult to calibrate. CoreXY printers use two motors working together with belts to move the print head in the X and Y directions while keeping the motors stationary. This design reduces moving mass and improves speed and accuracy.

I also researched the advantages of the CoreXY system and found that it offers better stability, faster printing, and cleaner movement compared to traditional designs. However, CoreXY printers require proper belt alignment and a rigid frame for good performance. This made me realize the importance of mechanical design and precision in 3D printers.

Based on this research, I decided to design my project, Rookie Centuri, using the CoreXY system. I chose a compact build volume of 110 × 110 × 110 mm so that I could focus on learning calibration, belt tuning, and slicer settings without the complexity of a large printer. This research stage helped me understand the working principles of modern 3D printers and guided my design decisions.
<img width="1235" height="1441" alt="image" src="https://github.com/user-attachments/assets/a213c87c-34b0-4045-aef5-9de264982664" />

### Day 2: Making the BOM for a 110×110×110 mm Rookie Centuri

After completing my initial research, I moved on to creating the Bill of Materials (BOM) for my 100×100×100 mm 3D printer. I realized that before actually building a machine, it is very important to clearly understand what components I am working with and why they are needed. A 3D printer is a combination of mechanical, electrical, and software systems, and the BOM connects all of them together.

While preparing the BOM, I carefully listed each major part such as the frame, motion system, motors, belts, electronics, power supply, and hotend. Doing this helped me understand how every component affects the printer’s performance. For example, choosing the right motors impacts precision, the frame material affects rigidity, and the electronics decide how well everything can be controlled and upgraded later.

Creating the BOM also made me think about future development and improvements. If I know exactly what parts I am using, it becomes easier to upgrade the printer later, troubleshoot problems, or modify the design. This step is not just about buying parts, but about learning how different components interact with each other inside a working machine.
<img width="577" height="576" alt="image" src="https://github.com/user-attachments/assets/5f450327-07a9-4ba6-ac85-33087e6cd9a2" />
<img width="565" height="258" alt="image" src="https://github.com/user-attachments/assets/04d50563-3333-4e9d-9894-050e4e4deead" />

### lets start designing 3d parts for this printer
With the research done and the BOM prepared, the next step in my project was to start designing the 3D-printed parts for the 100×100×100 mm 3D printer. This stage felt important because these parts will physically hold the entire printer together and directly affect its accuracy, strength, and reliability.

### Foot Mount Design Completed – Moving to Bottom Frame
Successfully designed the foot mount for the 3D printer. This component will help provide proper support and stability to the printer by evenly distributing its weight on the surface. With the foot mount design completed, the focus will now shift toward designing the bottom frame, which will act as the foundation for the entire printer structure.
<img width="737" height="477" alt="image" src="https://github.com/user-attachments/assets/838d1872-ddab-4766-abe0-3a68ace2ed97" />
<img width="860" height="478" alt="image" src="https://github.com/user-attachments/assets/c289d072-373b-4a6a-8ba2-c09817d94f77" />

### Designing the Core Mounts for the Frame
Today I focused on designing the main mounting components of the frame. I successfully designed the bottom mount, left motor mount, right motor mount, and the top mount. These parts are essential for holding the structure together and ensuring proper alignment of the motors and the overall frame.

The foot mount, which was designed yesterday, was kept in mind while working on today’s designs. I made sure that the bottom mount properly supports and aligns with the foot mount so that they can be attached securely. This was important for maintaining stability and balance when the frame is placed on a surface.

With the core mounts now designed and checked for compatibility with each other, the basic structural layout of the printer is taking shape. Having completed this stage, the next step will be to move forward and start designing the gantry system, which will play a key role in motion and precision.

Top Mount
<img width="832" height="488" alt="image" src="https://github.com/user-attachments/assets/0412e2f1-ee95-4daf-9d81-56fcd85898aa" />

<img width="616" height="617" alt="image" src="https://github.com/user-attachments/assets/37d7cd50-1fe5-4e2a-b62f-bf21a8f4f390" />

<img width="565" height="573" alt="image" src="https://github.com/user-attachments/assets/fb7e5e92-e1cd-461f-bd18-7f8ed6f6224d" />

<img width="841" height="301" alt="image" src="https://github.com/user-attachments/assets/c7d307c7-b1fe-4e0f-938e-a7b817b6a053" />


bottom Mount
<img width="790" height="680" alt="image" src="https://github.com/user-attachments/assets/26404a02-32a0-491f-9cc0-f4142a8b00bb" />

<img width="727" height="488" alt="image" src="https://github.com/user-attachments/assets/4030da31-a2ed-4c96-be04-4b389d7654f2" />

<img width="765" height="460" alt="image" src="https://github.com/user-attachments/assets/ae98fb34-adb4-4dd9-951d-a810537d518b" />


Left motor mount
<img width="647" height="605" alt="image" src="https://github.com/user-attachments/assets/1b056f2a-e480-477a-a8e9-7e168fdef692" />

<img width="601" height="615" alt="image" src="https://github.com/user-attachments/assets/1834625f-804d-4fd1-8295-31bc078624db" />


Right Motor Mount
<img width="872" height="581" alt="image" src="https://github.com/user-attachments/assets/acb3263d-dec4-490b-8893-36927cb2f0bd" />

<img width="751" height="603" alt="image" src="https://github.com/user-attachments/assets/12d08161-ede1-435a-a2df-0d30e6e71570" />

Made multiple 3d parts
men i m working on this from Morning

NOW ONLY IDLERS ARE REMAINING.
Motherboard Mount
<img width="490" height="655" alt="image" src="https://github.com/user-attachments/assets/82607530-6294-4898-8625-e12e13b2b573" />


Print Bed Holder
<img width="587" height="557" alt="image" src="https://github.com/user-attachments/assets/64449dd3-348d-44a0-af2e-1457e215edf8" />

<img width="486" height="535" alt="image" src="https://github.com/user-attachments/assets/a8d5b1da-58ac-4a92-9f93-97b11b8131f5" />


Glass Bed Holder
<img width="411" height="673" alt="image" src="https://github.com/user-attachments/assets/ec7facde-95ff-4a6e-8e8a-9ee8e5a56106" />

<img width="778" height="556" alt="image" src="https://github.com/user-attachments/assets/6864b8a3-b1a3-4fe7-86ca-17353b2ae739" />


Extruder part no.1 this would hold extruder
<img width="832" height="512" alt="image" src="https://github.com/user-attachments/assets/9b0a66ec-f6c1-4809-b9a4-45595ae1e7ed" />

<img width="531" height="712" alt="image" src="https://github.com/user-attachments/assets/b301923e-0731-434d-a3da-6cf598d147bf" />

<img width="675" height="463" alt="image" src="https://github.com/user-attachments/assets/43800856-8751-4ac8-833c-16465529c4e1" />

Extruder Part no.2
<img width="443" height="715" alt="image" src="https://github.com/user-attachments/assets/f46db3ae-070c-45cd-843b-0b069c2e6242" />

<img width="265" height="686" alt="image" src="https://github.com/user-attachments/assets/0317c242-9830-4f35-8c15-4f0d79c9f28e" />

Gantry Carriage
<img width="577" height="457" alt="image" src="https://github.com/user-attachments/assets/bb1a3994-87dc-46c4-8e57-39057b25456a" />

made the gantry system of printer
worked on making the gantry system, focusing on the structure, alignment, and overall rigidity. I designed and assembled the gantry to ensure smooth movement and proper support, which is important for stability and accurate operation.

This step helped me better understand how mechanical systems work together and how small alignment changes can affect performance. With the gantry system completed, the project is moving steadily forward toward final assembly and testing.

y carriage left
<img width="703" height="653" alt="image" src="https://github.com/user-attachments/assets/2d17d2a1-b8a7-43b5-bfdf-12605d861992" />

<img width="683" height="645" alt="image" src="https://github.com/user-attachments/assets/dd74634e-5101-4874-91a8-85be62411b55" />


Y carriage right
<img width="662" height="616" alt="image" src="https://github.com/user-attachments/assets/6a5284e4-30de-4597-b221-470726e6a1a5" />

<img width="691" height="472" alt="image" src="https://github.com/user-attachments/assets/d8656563-ceb4-4d70-be2a-802690084b1b" />


Left Idler
<img width="736" height="647" alt="image" src="https://github.com/user-attachments/assets/e91e8831-55d9-4ad2-aa56-2cb2586b39f0" />

<img width="552" height="637" alt="image" src="https://github.com/user-attachments/assets/fd6297f6-b5bb-4218-ba42-c57b2c49c00d" />


Right Idler
<img width="717" height="682" alt="image" src="https://github.com/user-attachments/assets/23caf27e-23f1-4463-98fb-d5ecc3ac7de1" />

<img width="652" height="658" alt="image" src="https://github.com/user-attachments/assets/582244bf-0430-4548-bd03-679f323fff07" />


Z endstop
<img width="748" height="533" alt="image" src="https://github.com/user-attachments/assets/47df7000-50e3-4f9c-b748-23190ed2cf88" />

<img width="757" height="467" alt="image" src="https://github.com/user-attachments/assets/4df5b497-98e4-4306-b0ec-4ad257109501" />











