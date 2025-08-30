






Project Report
On
Online Doctor Booking in Android



   Under the guidance of 			             Submitted By 
 Write Your Guidance Name                       Write Your Name
Saubhik Bandopadhyay                              Debarghaya Bhaumik  



CERTIFICATE

This is to certify that the project entitled as “Online Doctor Booking” which has been completed and submitted by Debarghaya Bhaumik is a bonafied work by them and has been completed under my guidance and supervision.

Signature of the Students			               Signature of Trainer
Debarghaya Bhaumik                                          Saubhik  Bandopadhyay








	





SELF CERTIFICATE


This is to certify that the dissertation / project report entitled “Online Doctor Booking” is done by us is an authentic word carried out under the guidance of  Saubhik Bandopadhyay.

Signature of the Students :-		                       
Debarghaya Bhaumik	   					                    

								       

 
ACKNOWLEDGEMENT


A project like this one involves many people and would be incomplete without the mention of those people whose guidance and encouragement helped in the successful completion of the project. Our heartily thanks to Mr. Saubhik Bandopadhyay  for his effort towards our project. We are also thankful to many people whose timely help but paucity of space is restricting us from mentioning their names.
 
						      Debarghaya Bhaumik				     
 
DECLARATION

We hereby declare that the work is being presented in the project report entitled “Online Doctor Booking” . It is an authentic record of our work carried out under the able guidance of Saubhik Bandopadhyay.. The work has been carried out at Amity University Kolkata.

						    
	                                    
						 

CONTENTS
1.	 Objective
2.	System Analysis
2.1	Introduction
2.2	Analysis Model
2.3	Hardware and Software Specifications
3.	System Design
3.1	SDLC
3.2	E-R Diagram
4.	System Development Environment
4.1	Introduction to Android
5.	Feasibility Study
6.	Database Screenshots
7.	Project Codes
8.	Project Screenshots
9.	Conclusions
10.	Bibliography

 
Objective

The objective of this thesis was to develop an Online Doctor's Booking App by Specific Location and Specialist For Android Operating System. The purpose of implementing this application was to create a system through which a patient can easily search and make an online appointment for a doctor just by sitting at home.

The reason behind creating this system was the “trend of private medical clinics” and manual medical file keeping system. Online appointment aims to improve quality medical care by bringing all medical clinics of the city at one platform, eliminating long waiting lines and replacing manual medical file keeping with an online.

The application was successfully implemented by using famous technologies and programming languages. This application does not aim to target any specific group but every individual who wants to search a doctor and that is why it was kept in mind to keep the user interface simple and friendly while building this application. Like all other applications, this application also has a client side and a server side. This application was developed by using Android Studio.

For now, basic functionalities have been implemented but for the future, work will be done to link pharmacies and laboratories to the system. Online follow-up for the distant patients is another feature that is aimed to add at later stages.  
Introduction :
Health care is one of the fastest growing industry all over the world. Before the last few years, medical appointments were usually taken on the phone calls or by visiting the hospitals in person. This process needed the involvement of individuals so, the ability to take appointment was restricted to the availability of schedulers, phone lines or the physical presence of a person. With the growth of time, everybody demanded timeless and efficient medical care delivery because manual appointments (that requires the physical presence of both individuals) and long waiting lines have formed an irritating situation for the healthcare institutions. So, it created a need for such an integrated health care system that could deliver seamless care to both outpatients as well as inpatients. The emergence of online
appointment system offered timeless and efficient access to health care services.

Therefore, for hospitals and other medical societies, online appointment booking has a great. Booking appointment online has become a new trend in the past few years and is considered as one of the key processes in the healthcare industry. well-designed appointment system supposed to improve patients’ satisfaction by
reducing cost and time of clinics and hospitals especially in the busy lives we are leading today.

Nowadays there are many kinds of online appointment tools available in the market which are easy to set up and not too much expensive. Online scheduling system offers valueadded services and lots of benefits to the doctors and patients. It makes the patient
appreciated by eliminating the hassle of long waiting times. Online Doctor Booking  are also getting popular because of its low-cost availability.

Main Purpose :
The main purpose of this project is to link and bring all major private medical clinics of the city (of my country) to a single platform. So that patients can easily get access to the doctor's profile and make online appointments.

Objective of the Project :
The main objective of the thesis is to provide quality medical care to the patients by bringing all medical practitioners of the city to a single platform so that everybody can easily access them and make appointments.
Aim of the Project :
The aim of this project is to create a platform where patients and doctors can access /interact efficiently with each other and provide ease and comfort to the patients. It also aims to resolve the problems that patients have to face while taking appointments and keeping medical files. Patients can choose a medical practitioner based on their professional profile and other patient's reviews.
Following features will be added in the future:
•	Online follow up with doctors (specially for distant patients)
•	Linking laboratory and pharmacy so that medical store administrator can view suggested prescription and laboratory can view clinical tests recommended by the doctor. This feature aims to eliminate paper-based prescriptions.




Study Limitation :
The lack of time was the main the limitation. Secondly, because there is no such system in my country so there may be some difficulties to implement and convince people to use this system.
APPLICATION TECHNOLOGIES :
The purpose of this project is to build an Online Appointment and Database Management System. It is important for the user to understand how this application works and knowing the technologies that are used to implement this project. For a better understanding, all
steps are described in detail to give a full overview of the system.
Hardware requirements To Develop This App
1.	Processor i3 or above.
2.	RAM 4 GB or above.
3.	HDD 40 GB or above.
4.	Keyboard.
5.	Mouse.
6.	Monitor CRT, LCD, LED etc.
Software requirements To Develop This App
1.	Windows Operating System. (Windows  7, 8, 8.1, 10 etc.)
2.	Android Studio.
3.	MySql Datbase. 

Requirements To Install This App in Your Android Mobile:
1.	RAM 1 GB or above.
2.	Minimum 20 Mb space for install this App.
3.	Minimum version of Android Kilkat.




E-R Diagram
A basic ER model consists of objects called entities and specifies relationship among those entities. Purpose of this diagram is not to define any functionality rather show association and dependency among entities. ER diagram is drawn with "rectangular boxes" as entities and the "straight lines" showing the relationship between these boxes. An entity is an object or a thing that has an independent existence and can be easily differentiated from others. Each entity has some attributes like name, age, address, department etc. In the following diagram the doctor, patient, appointment, admin etc, all are different entities. So, an entity can be a person, animal, plant, event or a company. Entities consisting of similar attributes make the entity sets. These entities have some association among each other which make a relationship. These relationships can be "one to one" or "one to many" or "many to many". For example, a doctor and department can have "one to many" relationships, means one department can have many doctors but one doctor is related to only one department.


 

 
Database Screenshots
Doctor Table :
 

Doctor_timing:
 


Appointment :
 
Feedback :
 




Project Codes
AndroidManifiest :
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.programming.cpc.onlinedoctorbooking">
    <uses-permission android:name="android.permission.INTERNET"></uses-permission>
    <uses-permission android:name="android.permission.CALL_PHONE" />
    <uses-permission android:name="android.permission.READ_PHONE_STATE" />

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <activity android:name=".FeedbackActivity"></activity>
        <activity android:name=".SearchDoctorActivity"></activity>
        <activity android:name=".DoctorListActivity"></activity>
        <activity android:name=".DoctorDetails"></activity>
        <activity android:name=".AppointmentActivity"></activity>
        <activity android:name=".HomeActivity"></activity>
        <activity android:name=".GiveFeedbackActivity"></activity>
        <activity android:name=".FixedAppointment"></activity>
        <activity android:name=".AppointmentHistory"></activity>
        <activity android:name=".PatientAppointment"></activity>
    </application>

</manifest>
Layouts (Code For Design Part):
activity_main.xml :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/back"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/startbtn"
        android:layout_width="157dp"
        android:layout_height="62dp"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="30dp"
        android:contentDescription="@android:string/unknownName"
        app:srcCompat="@drawable/start" />
</RelativeLayout>

search_doctor_activity:
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/background">

    <AutoCompleteTextView
        android:id="@+id/locationtxt"
        android:layout_width="225dp"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="160dp"
        android:hint="Enter Your Location"
        android:singleLine="true"
        android:imeOptions="actionNext"
        />

    <AutoCompleteTextView
        android:id="@+id/specialisttxt"
        android:layout_width="225dp"
        android:layout_height="wrap_content"
        android:layout_centerInParent="true"
        android:hint="Enter Doctor Specialist"
        android:imeOptions="actionDone"
        android:singleLine="true" />

    <Button
        android:id="@+id/btnSearch"
        android:layout_width="225dp"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="159dp"
        android:background="@android:color/holo_blue_dark"
        android:text="Search" />

    <TextView
        android:id="@+id/message"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginBottom="74dp"
        android:textColor="@android:color/holo_red_light"
        android:textSize="20dp" />
</RelativeLayout>

doctor_list.xml :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ListView
        android:id="@+id/doctorList"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:background="@drawable/background" />
</RelativeLayout>

doctor_details.xml :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/background">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="145dp"
        android:orientation="horizontal">

        <ImageView
            android:id="@+id/docimageView"
            android:layout_width="349dp"
            android:layout_height="153dp"
            android:layout_alignParentStart="true"
            android:layout_alignParentTop="true"
            android:layout_weight="1" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="49dp"
        android:layout_alignParentStart="true"
        android:layout_marginTop="150dp"
        android:layout_weight="1"
        android:orientation="horizontal">

        <TextView
            android:id="@+id/docName"
            android:layout_width="530dp"
            android:layout_height="match_parent"
            android:layout_alignParentStart="true"
            android:layout_alignParentTop="true"
            android:layout_marginTop="0dp"
            android:layout_weight="1"
            android:background="@android:color/black"
            android:padding="5dp"
            android:paddingLeft="20dp"
            android:textColor="@android:color/background_light"
            android:textSize="25dp"
            android:textStyle="bold" />

        <Button
            android:id="@+id/buttonCall"
            android:layout_width="match_parent"
            android:layout_height="49dp"
            android:layout_weight="1"
            android:background="@android:color/holo_green_light"
            android:text="CALL" />
    </LinearLayout>

    <TableLayout
        android:layout_width="match_parent"
        android:layout_height="311dp"
        android:layout_marginTop="200dp"
        android:background="@android:color/background_light">

        <TableRow
            android:layout_width="match_parent"
            android:layout_height="33dp"
            android:background="@android:color/background_light"
            android:showDividers="beginning|middle|end">

            <TextView
                android:id="@+id/textView4"
                android:layout_width="149dp"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:text="Degree"
                android:textColor="@android:color/holo_blue_dark"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/degreetxt"
                android:layout_width="235dp"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:textColor="@android:color/background_dark"
                android:textSize="20dp" />
        </TableRow>

        <TableRow
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@android:color/background_light">

            <TextView
                android:id="@+id/textView6"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:padding="10dp"
                android:text="Fees"
                android:textColor="@android:color/holo_blue_dark"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/feestxt"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:textColor="@android:color/background_dark"
                android:textSize="20dp" />
        </TableRow>

        <TableRow
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@android:color/background_light">

            <TextView
                android:id="@+id/textView8"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:text="Days"
                android:textColor="@android:color/holo_blue_light"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/daystxt"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:textColor="@android:color/background_dark"
                android:textSize="20dp" />
        </TableRow>

        <TableRow
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@android:color/background_light">

            <TextView
                android:id="@+id/textView10"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:text="Timing"
                android:textColor="@android:color/holo_blue_light"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/timetxt"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:textColor="@android:color/background_dark"
                android:textSize="20dp" />
        </TableRow>

        <TableRow
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@android:color/background_light">

            <TextView
                android:id="@+id/textView12"
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:padding="10dp"
                android:paddingTop="50dp"
                android:text="Chamber"
                android:textColor="@android:color/holo_blue_light"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/chambertxt"
                android:layout_width="100dp"
                android:layout_height="80dp"
                android:maxLines="3"
                android:padding="10dp"
                android:textColor="@android:color/background_dark"
                android:textSize="20dp" />
        </TableRow>
    </TableLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentStart="true"
        android:orientation="horizontal">

        <Button
            android:id="@+id/feedbackbtn"
            android:layout_width="372dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@android:color/holo_blue_light"
            android:text="FEEDBACK"
            android:textColor="@android:color/background_light"
            android:textSize="20dp" />

        <View
            android:id="@+id/divider"
            android:layout_width="200dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="@android:color/background_light" />

        <Button
            android:id="@+id/appointmentbtn"
            android:layout_width="371dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:background="@android:color/holo_blue_light"
            android:text="APPOINTMENT"
            android:textColor="@android:color/background_light"
            android:textSize="20dp" />
    </LinearLayout>

</RelativeLayout>

patient_appoinment.xml :
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/background">

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="150dp"
        android:background="@android:color/background_light">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView15"
                android:layout_width="117dp"
                android:layout_height="36dp"
                android:layout_marginLeft="30dp"
                android:layout_weight="1"
                android:padding="5dp"
                android:text="Appoinment ID"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/textView16"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginTop="-3dp"
                android:layout_weight="1"
                android:padding="10dp"
                android:paddingTop="20dp"
                android:text="15264"
                android:textSize="20dp" />


        </LinearLayout>

        <TableLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:layout_marginTop="50dp"
            android:layout_weight="1">

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="43dp">

                <TextView
                    android:id="@+id/textView17"
                    android:layout_width="117dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Date"
                    android:textSize="15dp"
                    android:textStyle="bold"
                    tools:layout_height="25dp" />

                <TextView
                    android:id="@+id/textView18"
                    android:layout_width="120dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Day"
                    android:textSize="15dp"
                    android:textStyle="bold" />

                <TextView
                    android:id="@+id/textView19"
                    android:layout_width="135dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Time"
                    android:textSize="15dp"
                    android:textStyle="bold" />
            </TableRow>

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="48dp">

                <TextView
                    android:id="@+id/textView20"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="16-10-2018"
                    android:textSize="15dp"
                    tools:layout_height="25dp" />

                <TextView
                    android:id="@+id/textView23"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Tuesday"
                    android:textSize="15dp" />

                <TextView
                    android:id="@+id/textView25"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="11 AM"
                    android:textSize="15dp" />
            </TableRow>

        </TableLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_marginTop="100dp"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button8"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:background="@android:color/holo_blue_dark"
                android:text="Update"
                android:textColor="@android:color/background_light"
                android:textSize="20dp" />

            <Button
                android:id="@+id/button9"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:background="@android:color/holo_blue_dark"
                android:text="Cancel"
                android:textColor="@android:color/background_light"
                android:textSize="20dp" />
        </LinearLayout>
    </RelativeLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="150dp"
        android:layout_marginTop="150dp"
        android:background="@android:color/background_light">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="horizontal">

            <TextView
                android:id="@+id/textView151"
                android:layout_width="117dp"
                android:layout_height="36dp"
                android:layout_marginLeft="30dp"
                android:layout_weight="1"
                android:padding="5dp"
                android:text="Appoinment ID"
                android:textSize="20dp"
                android:textStyle="bold" />

            <TextView
                android:id="@+id/textView161"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_marginTop="-3dp"
                android:layout_weight="1"
                android:padding="10dp"
                android:paddingTop="20dp"
                android:text="13587"
                android:textSize="20dp" />


        </LinearLayout>

        <TableLayout
            android:layout_width="match_parent"
            android:layout_height="60dp"
            android:layout_marginTop="50dp"
            android:layout_weight="1">

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="43dp">

                <TextView
                    android:id="@+id/textView171"
                    android:layout_width="117dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Date"
                    android:textSize="15dp"
                    android:textStyle="bold"
                    tools:layout_height="25dp" />

                <TextView
                    android:id="@+id/textView181"
                    android:layout_width="120dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Day"
                    android:textSize="15dp"
                    android:textStyle="bold" />

                <TextView
                    android:id="@+id/textView191"
                    android:layout_width="135dp"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Time"
                    android:textSize="15dp"
                    android:textStyle="bold" />
            </TableRow>

            <TableRow
                android:layout_width="match_parent"
                android:layout_height="48dp">

                <TextView
                    android:id="@+id/textView201"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="18-10-2018"
                    android:textSize="15dp"
                    tools:layout_height="25dp" />

                <TextView
                    android:id="@+id/textView23"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="Thursday"
                    android:textSize="15dp" />

                <TextView
                    android:id="@+id/textView251"
                    android:layout_width="wrap_content"
                    android:layout_height="match_parent"
                    android:gravity="center"
                    android:text="11 AM"
                    android:textSize="15dp" />
            </TableRow>

        </TableLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:layout_marginTop="100dp"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button81"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:background="@android:color/holo_blue_dark"
                android:text="Update"
                android:textColor="@android:color/background_light"
                android:textSize="20dp" />

            <Button
                android:id="@+id/button91"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:background="@android:color/holo_blue_dark"
                android:text="Cancel"
                android:textColor="@android:color/background_light"
                android:textSize="20dp" />
        </LinearLayout>
    </RelativeLayout>
</RelativeLayout>

Coding (Java Programs) :

MainActivity.java :

package com.programming.cpc.onlinedoctorbooking;

import android.content.Intent;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.ImageView;

public class MainActivity extends AppCompatActivity
{
    ImageView start;
    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        start = (ImageView) findViewById(R.id.startbtn);

        start.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View v)
            {
                Intent intent = new Intent(MainActivity.this,HomeActivity.class);
                startActivity(intent);
            }
        });

    }
}

SearchDoctorActivity :
package com.programming.cpc.onlinedoctorbooking;

import android.content.Intent;
import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.widget.ArrayAdapter;
import android.widget.AutoCompleteTextView;
import android.widget.Button;
import android.widget.TextView;

import java.util.Arrays;
import java.util.List;

public class SearchDoctorActivity extends AppCompatActivity
{
    AutoCompleteTextView location,specialist;
    Button search;
    TextView emessage;
    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.search_doctor_activity);

        String loc[]={"Rajerhat","Salt Lake","New Town"};
        location = (AutoCompleteTextView) findViewById(R.id.locationtxt);
        ArrayAdapter<String> adp=new ArrayAdapter<String>(SearchDoctorActivity.this, android.R.layout.simple_dropdown_item_1line,loc);
        location.setThreshold(1);
        location.setAdapter(adp);

        String spe[]={"General Physician","Urologist","Cardiologist","Neurologist","Gastroentrologist"};
        specialist = (AutoCompleteTextView) findViewById(R.id.specialisttxt);
        ArrayAdapter<String> adp1=new ArrayAdapter<String>(SearchDoctorActivity.this, android.R.layout.simple_dropdown_item_1line,spe);
        specialist.setThreshold(1);
        specialist.setAdapter(adp1);

        search = (Button) findViewById(R.id.btnSearch);

        emessage = (TextView) findViewById(R.id.message);

        Bundle bundle = getIntent().getExtras();

        if(bundle!=null)
        {
            String msg = bundle.getString("emsg").toString();

            if(msg!=null)
            {
                emessage.setText(msg);
            }
        }

        search.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View v)
            {
                String l = location.getText().toString();
                String s = specialist.getText().toString();

                Intent intent1 = new Intent(SearchDoctorActivity.this,DoctorListActivity.class);
                intent1.putExtra("location",l);
                intent1.putExtra("specialist",s);
                startActivity(intent1);
            }
        });

    }
}

GetAllDoctors :

package com.programming.cpc.onlinedoctorbooking;

import android.graphics.Bitmap;
import android.graphics.BitmapFactory;

import org.json.JSONArray;
import org.json.JSONException;
import org.json.JSONObject;

import java.io.IOException;
import java.net.MalformedURLException;
import java.net.URL;


public class GetAllDoctors
{
    public static String[] ids;
    public static String[] degrees;
    public static Bitmap[] images;
    public static String[] names;

    public static final String JSON_ARRAY="result";
    public static final String DOCTOR_ID = "doctorid";
    public static final String DOCTOR_URL = "url";
    public static final String DOCTOR_NAME = "name";
    public static final String DOCTOR_DEGREE = "degree";
    private String json;
    private JSONArray urls;

    public GetAllDoctors(String json)
    {
        this.json = json;
        try
        {
            JSONObject jsonObject = new JSONObject(json);
            urls = jsonObject.getJSONArray(JSON_ARRAY);
        }
        catch (JSONException e)
        {
            e.printStackTrace();
        }
    }

    private Bitmap getImage(JSONObject jo)
    {
        URL url = null;
        Bitmap image = null;
        try
        {
            url = new URL(jo.getString(DOCTOR_URL));
            image = BitmapFactory.decodeStream(url.openConnection().getInputStream());
        }
        catch (MalformedURLException e) {
            e.printStackTrace();
        }
        catch (IOException e) {
            e.printStackTrace();
        }
        catch (JSONException e) {
            e.printStackTrace();
        }
        return image;
    }

    public void getAllDoctors() throws JSONException
    {
        ids = new String[urls.length()];
        images = new Bitmap[urls.length()];
        degrees = new String[urls.length()];
        names = new String[urls.length()];

        for(int i=0;i<urls.length();i++)
        {
            ids[i] = urls.getJSONObject(i).getString(DOCTOR_ID);
            names[i] = urls.getJSONObject(i).getString(DOCTOR_NAME);
            degrees[i] = urls.getJSONObject(i).getString(DOCTOR_DEGREE);
            JSONObject jsonObject = urls.getJSONObject(i);
            images[i]=getImage(jsonObject);
        }
    }
}
DoctorDetails :

package com.programming.cpc.onlinedoctorbooking;

import android.graphics.Bitmap;
import android.graphics.BitmapFactory;
import java.net.URL;
import android.Manifest;
import android.app.ProgressDialog;
import android.content.Intent;
import android.content.pm.PackageManager;
import android.net.Uri;
import android.os.Bundle;
import android.support.v4.app.ActivityCompat;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.widget.Button;
import android.widget.ImageView;
import android.widget.TextView;
import android.widget.Toast;

import com.android.volley.AuthFailureError;
import com.android.volley.Request;
import com.android.volley.RequestQueue;
import com.android.volley.Response;
import com.android.volley.VolleyError;
import com.android.volley.toolbox.StringRequest;
import com.android.volley.toolbox.Volley;

import org.json.JSONArray;
import org.json.JSONException;
import org.json.JSONObject;

import java.util.HashMap;
import java.util.Map;

public class DoctorDetails extends AppCompatActivity
{
    private ImageView imageView;
    private TextView nametxt,degreetxt,feestxt,daystxt,timingtxt,chambertxt;
    String doctorid,name,fees,degree,days,timing,contactno,imgpath,chamber;

    Button call,feedback,appointment;

    RequestQueue queue1;

    ProgressDialog progressDialog;

    private static final int MAKE_CALL_PERMISSION_REQUEST_CODE = 1;

    public static String URL ="https://cpcbelgharia56.000webhostapp.com/healthcare/SearchDoctorById.php";

    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.doctor_details);
        Intent intent = getIntent();
        final int index = intent.getIntExtra(DoctorListActivity.BITMAP_ID,0);

        // Toast.makeText(getApplicationContext(),"INDEX:: "+index,Toast.LENGTH_LONG).show();

        imageView = (ImageView) findViewById(R.id.docimageView);


        doctorid = GetAllDoctors.ids[index];

        nametxt = (TextView) findViewById(R.id.docName);
        degreetxt = (TextView) findViewById(R.id.degreetxt);
        feestxt = (TextView) findViewById(R.id.feestxt);
        daystxt = (TextView) findViewById(R.id.daystxt);
        timingtxt = (TextView) findViewById(R.id.timetxt);
        chambertxt = (TextView) findViewById(R.id.chambertxt);

        feedback = (Button) findViewById(R.id.feedbackbtn);
        feedback.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View v)
            {
                Intent intent1= new Intent(DoctorDetails.this,FeedbackActivity.class);
                startActivity(intent1);
            }
        });

        appointment = (Button) findViewById(R.id.appointmentbtn);
        appointment.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View v)
            {
                Intent intent1= new Intent(DoctorDetails.this,AppointmentActivity.class);
                startActivity(intent1);
            }
        });

        call = (Button) findViewById(R.id.buttonCall);
        call.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View view)
            {


                if (!android.text.TextUtils.isEmpty(contactno)) {
                    if (checkPermission(Manifest.permission.CALL_PHONE)) {
                        String dial = "tel:" + contactno;
                        startActivity(new Intent(Intent.ACTION_CALL, Uri.parse(dial)));
                    } else {
                        Toast.makeText(DoctorDetails.this, "Permission Call Phone denied", Toast.LENGTH_SHORT).show();
                    }
                } else {
                    Toast.makeText(DoctorDetails.this, "Enter a phone number", Toast.LENGTH_SHORT).show();
                }
            }
        });

        if (checkPermission(Manifest.permission.CALL_PHONE))
        {
            call.setEnabled(true);
        }
        else
        {
            call.setEnabled(false);
            ActivityCompat.requestPermissions(this, new String[]{Manifest.permission.CALL_PHONE}, MAKE_CALL_PERMISSION_REQUEST_CODE);
        }

        progressDialog = ProgressDialog.show(DoctorDetails.this, "Please wait...", "We are Fetching Data From Server", false, false);
        progressDialog.show();

        queue1 = Volley.newRequestQueue(DoctorDetails.this);

        StringRequest request = new StringRequest(Request.Method.POST, URL, new Response.Listener<String>() {
            @Override
            public void onResponse(String response) {

                progressDialog.dismiss();
                //Toast.makeText(DoctorDetails.this, "Server Result: " + response, Toast.LENGTH_SHORT).show();
                // Log.i("My success",""+response);

                if (response != null)
                {

                    try
                    {
                        JSONObject jsonObj = new JSONObject(response);

                        // Getting JSON Array node
                        JSONArray students = jsonObj.getJSONArray("result");

                        // looping through All Contacts
                        for (int i = 0; i < students.length(); i++)
                        {
                            JSONObject c = students.getJSONObject(i);

                            name = c.getString("name");
                            degree = c.getString("degree");
                            fees = c.getString("fees");
                            days = c.getString("days");
                            timing = c.getString("timing");
                            contactno = c.getString("contactno");
                            imgpath = c.getString("imgpath");
                            chamber = c.getString("chamber");


                            // Toast.makeText(getApplicationContext(),"Name: "+name,Toast.LENGTH_SHORT).show();
                            // Bitmap img = getImage(imgpath);

                            nametxt.setText(name);
                            degreetxt.setText(degree);
                            feestxt.setText(fees);
                            daystxt.setText(days);
                            timingtxt.setText(timing);
                            chambertxt.setText(chamber);

                            imageView.setImageBitmap(GetAllDoctors.images[index]);

                        }

                    }
                    catch (final JSONException e)
                    {
                        //Log.e(TAG, "Json parsing error: " + e.getMessage());
                        runOnUiThread(new Runnable() {
                            @Override
                            public void run() {
                                Toast.makeText(getApplicationContext(),
                                        "Json parsing error: " + e.getMessage(),
                                        Toast.LENGTH_LONG)
                                        .show();
                            }
                        });

                    }
                }
                else
                {
                    //Log.e(TAG, "Couldn't get json from server.");
                    runOnUiThread(new Runnable() {
                        @Override
                        public void run() {
                            Toast.makeText(getApplicationContext(),
                                    "Couldn't get json from server. Check LogCat for possible errors!",
                                    Toast.LENGTH_LONG)
                                    .show();
                        }
                    });

                }




            }
        }, new Response.ErrorListener() {
            @Override
            public void onErrorResponse(VolleyError error) {

                progressDialog.dismiss();
                Toast.makeText(DoctorDetails.this, "my error :" + error, Toast.LENGTH_LONG).show();
                //Log.i("My error",""+error);

            }
        }) {
            @Override
            protected Map<String, String> getParams() throws AuthFailureError
            {

                Map<String, String> map = new HashMap<String, String>();
                map.put("doctorid",doctorid);
                return map;
            }
        };
        queue1.add(request);


    }

    private boolean checkPermission(String permission) {
        return android.support.v4.content.ContextCompat.checkSelfPermission(this, permission) == PackageManager.PERMISSION_GRANTED;
    }

    @Override
    public void onRequestPermissionsResult(int requestCode, @android.support.annotation.NonNull String[] permissions, @android.support.annotation.NonNull int[] grantResults) {
        switch(requestCode) {
            case MAKE_CALL_PERMISSION_REQUEST_CODE :
                if (grantResults.length > 0 && (grantResults[0] == PackageManager.PERMISSION_GRANTED)) {
                    call.setEnabled(true);
                    Toast.makeText(this, "You can call the number by clicking on the button", Toast.LENGTH_SHORT).show();
                }
                return;
        }
    }

    private Bitmap getImage(String jo)
    {
        URL url = null;
        Bitmap image = null;
        try
        {
            url = new URL(jo);
            image = BitmapFactory.decodeStream(url.openConnection().getInputStream());
        }
        catch (java.net.MalformedURLException e) {
            e.printStackTrace();
        }
        catch (java.io.IOException e) {
            e.printStackTrace();
        }

        return image;
    }
}

AppointmentHistory :

package com.programming.cpc.onlinedoctorbooking;

import android.content.Intent;
import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.widget.Button;

public class AppointmentHistory extends AppCompatActivity
{
    Button submit;
    @Override
    protected void onCreate(Bundle savedInstanceState)
    {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.appointment_login);

        submit = (Button) findViewById(R.id.button7);

        submit.setOnClickListener(new View.OnClickListener()
        {
            @Override
            public void onClick(View v)
            {
                Intent intent = new Intent(AppointmentHistory.this,PatientAppointment.class);
                startActivity(intent);
            }
        });
    }
}











                      

  



    













































Conclusions

The scope of the application I am developing is not too big, but I hope at least it would be a good solution to the prevailing problems of my City. As I have mentioned earlier there are a lot of small clinics in every next street, creating a very confusing problem for the public as well as new practitioners. So, this kind of system will help the users to choose which doctor to consult, get an appointment online and equal opportunity to all practitioners to be reached by the public. So it is very important to keep the user interface very easy to understand and simple to use. So, Usually developing any system comprises of three basic steps planning, design, and the develop phase. After finalizing the basic requirements that should be met by the system, it was also important to decide which technologies to use for the development of this system. For this purpose, I took help from the web and carefully studied already existed similar Apps. Use class diagram, and ER diagram are used to better explain the system and its working. The purpose for drawing use case diagram was to explain not only functionalities but also to write down the requirements of each user very clearly. The class diagram was drawn to explain the relationship and behavior of entities. 
For now, I have chosen and working on some basic functionalities like an online appointment and online patient review. But for the future, I would like to extend my system to the pharmacies and laboratories. For example, different pharmacies and laboratories can also be registered with the system. And when the doctor prescribes some medicine or writes some tests, the patient can just go to any registered pharmacy and get the medicine after showing his ID. In the same way, if a doctor writes some tests, the patient can go to any registered laboratory. Registered pharmacies and laboratories would have some limited access to the patient data like what is prescribed by the doctor and they can add the report result into the patient's  database. Online follow up is another feature that I would like to add in my system at some later stages. The idea of this feature came into my mind because the patients living in faraway places have to come multiple times for the “laboratory test results” and “doctors' advice/ follow-up appointment” based on those tests. So, after the
laboratory tests, patients just have to book an online time and they can have an online conversation with some fewer fees. Online payment is again another feature I would like to add at later stages.


