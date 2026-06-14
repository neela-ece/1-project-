import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()import streamlit as st
from datetime import date

st.set_page_config(page_title="AI Smart Study Planner", page_icon="📚")

st.title("📚 AI Smart Study Planner")

student_name = st.text_input("Enter Your Name")

subjects = st.text_area(
    "Enter Subjects (separated by commas)",
    placeholder="Math, Science, English"
)

study_hours = st.slider(
    "Available Study Hours Per Day",
    1, 12, 4
)

exam_date = st.date_input(
    "Exam Date",
    min_value=date.today()
)

if st.button("Generate Study Plan"):

    subject_list = [s.strip() for s in subjects.split(",") if s.strip()]

    if not subject_list:
        st.error("Please enter at least one subject.")
    else:
        days_left = (exam_date - date.today()).days

        st.success(f"Hello {student_name}!")
        st.write(f"Days remaining: {days_left}")

        hours_per_subject = round(
            study_hours / len(subject_list), 1
        )

        st.subheader("📅 Daily Study Plan")

        for subject in subject_list:
            st.write(
                f"✅ {subject}: {hours_per_subject} hour(s) per day"
            )

        st.balloons()
