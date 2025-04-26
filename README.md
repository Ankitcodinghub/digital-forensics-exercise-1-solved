# digital-forensics-exercise-1-solved
**TO GET THIS SOLUTION VISIT:** [Digital-Forensics Exercise #1 Solved](https://www.ankitcodinghub.com/product/digital-forensics-exercise-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94813&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Digital-Forensics Exercise #1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this lab, you will first learn how to build your own forensics workstation by using some popular open source digital forensics tools, including The Sleuth Kit (TSK) and Autopsy Browser, dcfldd. Then, you will look at the data structures that are involved with partitioning based on two sample disk image files of a popular disk partitioning system, PC-based Partitions (or the master boot record (MBR) partitioning scheme), as used in MS-DOS, Microsoft Windows and Linux on PC compatible computer systems [1,2]. Two sample disk image files include the disk image named “thumbimage_ntfs.dd” provided on the course website in CourseLink and a publicly available extended partition system image [5]. Through examining partition tables, you should be able to know how to conduct a disk volume analysis as well as extract partitions from a disk image. Also, you will start to design and develop you own digital forensic tool, particularly, a volume analysis tool using scripting language like Python, Perl or Linux Shell Scripting.

This lab will be graded, and has to be completed INDIVIDUALLY. After you have finished the tasks, please submit your answers through Courselink

2. Environment Setup

1) Build up your Forensics Workstation with Kali Linux

Please read Chapter 3 of the textbook, build up your Forensics Workstation with Kali Linux onto your computer.

1 Copyright © 2019 Xiaodong Lin, University of Guelph.

This lab may not be redistributed or used without written permission.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

Figure 1. Required Environment Settings

2) Download extended DOS partition testing tool, “1-extend-part.zip”, where a file called ext-part-test-2.dd inside the zip archive (1-extend-part.zip) is a disk image for the purpose of learning extended partition concepts [5], and upload it to your computer forensics workstation.

To download this tool, go to the following link

http://dftt.sourceforge.net/test1/index.html

3) Download the disk image named “thumbimage_ntfs.dd” from the course website in the

section “\Datasets\Disk Images”, and upload it to your computer forensics workstation. 3. Exercises (4 marks, 1 mark each)

1) Which of the following statements is not true regarding PC-based Partitions (DOS-style partitions)? (Select One or More Answer Choices) c

a) DOS-style partition systems use MBR (Master Boot Record) to store the partitioning information on a hard disk drive.

b) MBR only holds descriptors for 4 partitions, called the primary partitions. The maximum number of primary partitions supported by MBR is 4.

c) You create a DOS partition (or logical drive), you must be sure to use up all of the hard disk space.

d) MBR contains the disk’s partition table and the code to bootstrap an operating system. e) MBR is located in the first sector of the hard drive.

2) When is the MBR created? c (Select the best answer) a) Low-level Format

b) High-level Format

c) Partitioning

d) OS Install

3) A partition structure defines how information is structured on the partition, where

partitions begin and end, and also the code that is used during startup if a partition is

bootable. MBR and GPT are two different ways of storing the partitioning information on

a drive. What does GPT stands for? GUID Partition Table,The location information of the partitioned table is stored in the GPT header

4) How big, in bytes, is MBR for 1TB Hard Drive? _512 byte. 4. Hands-onActivities

1) Extract the MBR from the disk image “thumbimage_ntfs.dd” (1 mark)

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

Activities: Extract the MBR from the disk image provided by using the ‘dcfldd’ tool. Hint: You have to know the location (the starting point and length) of a MBR in order to

extract it.

Writing down your command(s) issued to extract the MBR from “thumbimage_ntfs.dd”?

dcfldd if=thumbimage_ntfs.dd bs=512 skip=0 count=1 of=mbrfat.dd 2) Analyze the disk image “thumbimage_ntfs.dd” (1 mark)

Activities: Analyze the disk image provided and fill the following table with the appropriate values in the right column. Except partition entry value and partition type, all

other values are in decimal format.

If any partition table entry’s 16-byte value is all 0, it means that the corresponding partition doesn’t exist. Thus, you don’t have to fill in the table for it.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #0 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0003 0200 0707 e0c9 6100 0000 9fc9 0300

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB)

</div>
<div class="column">
Partition table

Cylinder:0, head:3,sector:2 Cylinder:201, head:7,sector:224 0x00000061 =&gt; 97

248223

0x0030c99f ×512B = 248233×512B = 121.2026MB 0x07=&gt;NTFS

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #1 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address

Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

3) Extract the partition(s) from the disk image “thumbimage_ntfs.dd” (1 mark) Activities: Extract the first partition from the disk image provided by using the ‘dcfldd’

tool.

Hint: You have to know the starting point and length of a partition in order to extract it.

Writing down your command(s) issued to extract the first partition from the disk image “thumbimage_ntfs.dd”?

dcfldd if=thumbimage_ntfs.dd bs=512 skip=97 count=248223 of=firstpartfat.dd

4) Perform a partition consistency check on disk image (2 marks)

Activities: Perform a partition consistency check on the disk image “thumbimage_ntfs.dd” and answer the following questions.

Is it possible to hide data on the disk which images are made of?

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #2 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #3 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

If yes, please explain why.

Yes, because there may be some storage areas that are not partitioned. If the area is not

partitioned, the MBR will not record information about the partition. So there could be hidden information

</div>
</div>
<div class="layoutArea">
<div class="column">
5) Analyze the Extended DOS Partition Testing Image “ext-part-test-2.dd” (8 marks) Activities: Analyze the Extended DOS Partition testing image “ext-part-test-2.dd” and

fill the following tables with the appropriate values in the right column. Except partition record value and partition type, all other values are in decimal format

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #0 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0001 0100 041f 3f19 3f00 0000 81cc 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address

</div>
<div class="column">
Primary Partition table

Cylinder:0, head:1,sector:1

Cylinder:25, head:31,sector:63 0x0000003f =&gt;63

52353

0x0000cc81 * 512B = 52353 * 512B = 25.5630 MB 0x04=&gt;FAT16

Cylinder:26, head:0,sector:1

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #1 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000 011a 041f 3f33 c0cc 0000 c0cc 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

</div>
</div>
<div class="layoutArea">
<div class="column">
Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address

Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address

</div>
<div class="column">
Cylinder:51, head:31,sector:63 0x0000ccc0=&gt;52416

52416

0x0000ccc0 * 512B = 52416 *512B = 25.59375 MB 0x04=&gt;FAT16

Cylinder:52, head:0,sector:1 Cylinder:77, head:31,sector:63

0x00019980=&gt;104832 52416

0x0000ccc0 * 512B = 52416 *512B = 25.59375 MB 0x04=&gt;FAT16

Cylinder:78, head:0,sector:1 Cylinder:154, head:31,sector:63

0x00026640=&gt;157248 155232

0x00025e60 * 512B = 155232 * 512B = 75.796875MB 0x05=&gt;extended

Extended Partition table #1

Cylinder:78, head:1,sector:1 Cylinder:103, head:31,sector:63

0x0000003f=&gt;63, 63+157248=157311 52353

0x0000cc81*512B = 52353*512B=25.5630MB 0x04=&gt;FAT16

Cylinder:104, head:1,sector:1

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #2 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000 0134 041f 3f4d 8099 0100 c0cc 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #3 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000 014e 051f 3f9a 4066 0200 605e 0200

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #0 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0001 014e 041f 3f67 3f00 0000 81cc 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #1 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0001 0168 041f 3f81 ffcc 0000 81cc 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

</div>
</div>
<div class="layoutArea">
<div class="column">
Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address

Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address

</div>
<div class="column">
Cylinder:129, head:31,sector:63

0x0000ccff =&gt; 52479,52479+157248=209727

52353

0x0000cc81*512B = 52353*512B=25.5630MB 0x04=&gt;FAT16

Cylinder:130, head:0,sector:1 Cylinder:154, head:31,sector:63

0x00019980=&gt; 104832,104832+157248=262080 50400

0x0000c4e0 *512B = 50400*512B = 24.609375 MB 0x05=&gt;extended

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #2 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0000 0182 051f 3f9a 8099 0100 e0c4 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #3 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Extended Partition table #2

Cylinder:130, head:1,sector:1 Cylinder:154, head:31,sector:63

0x0000003f=&gt;63,63+262080=262143 50337

0x0000c4a1*512B=50337*512B=24.57861 MB 0x06=&gt;FAT16

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #0 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
0001 0182 061f 3f9a 3f00 0000 a1c4 0000

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #1 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

Starting CHS address Ending CHS address

Starting LBA address Number of sectors in partition

size of the partition (MB) Type of partition

5. ToolDevelopmentActivities(3marks)

In this activity, you are required to complete the following task(s)

<ol>
<li>design and develop a volume analysis tool using scripting language like Python, Perl or Linux Shell Scripting. The tool should
<ul>
<li>list the details of each partition, including Starting CHS address, Starting LBA address, size of the partition (MB), and type of partition;</li>
<li>provide partition consistency check, particularly displaying a list of unpartitioned disk space if applicable, which are the space on a hard drive that hasn’t been partitioned yet or don’t belong to any partition.</li>
</ul>
</li>
<li>Output: your program will print out the layout of a disk volume with the following format Partitions
Seq. # Starting CHS Starting LBA Size (MB) Type
</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #2 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Partition #3 entry value in 16-byte Hexadecimal Format

</div>
</div>
</td>
<td></td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
Digital Forensics Hands-on Exercise #1

Consistency check (Unpartitioned disk space)

Seq. # Starting LBA Size (MB)

where output fields are separated by a tab character. Please note that the sequence number (Seq. #) starts with 1. The size in MB is displayed with three decimal places of precision.

The following is an example of the output

Partitions

Seq. # Starting CHS Starting LBA Size (MB) Type 1 C:0,H:1,S:1 63 63735.790 NTFS

2 C:1023,H:0,S:0 130530960 88889 NTFS

Consistency check (Unpartitioned disk space)

Seq. # Starting LBA Size (MB) 1 1 0.030

How to Run Your Tool

Assume that your tool is a shell script, called volumeanalysis.sh. Your program should run as follows:

./volumeanalysis.sh disk1.dd where disk1.dd is a disk image file.

Reference:

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
[1] Disk image. http://en.wikipedia.org/wiki/Disk_image

[2] Disk partitioning. [Online] Available at: http://en.wikipedia.org/wiki/Disk_partitioning

[3] Master boot record. [Online] Available at: http://en.wikipedia.org/wiki/Master_boot_record [4] Brian Carrier. File System Forensic Analysis. Addison-Wesley Professional; 1 edition (Mar 27 2005) ISBN-10: 0321268172

[5] Digital Forensics Tool Testing Images. [Online] Available at: http://dftt.sourceforge.net/

[6] Partitions and Volumes. [Online] Available at: http://www.yale.edu/pclt/BOOT/PARTITIO.HTM

</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
