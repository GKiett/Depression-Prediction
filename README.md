# 📊 Student Depression Analysis

Dự án này nhằm khám phá các yếu tố liên quan đến trầm cảm ở sinh viên, dựa trên tập dữ liệu khảo sát với hơn 27.000 mẫu. Dự án sử dụng Python và Jupyter Notebook để phân tích thống kê, trực quan hóa dữ liệu và đưa ra một số quan sát quan trọng.

---

## 🧾 Nội dung chính

- `student_depression_dataset.csv`: Dữ liệu khảo sát về sinh viên, gồm các yếu tố học tập, công việc, thói quen sinh hoạt và sức khỏe tâm thần.
- `depression.ipynb`: Jupyter Notebook phân tích dữ liệu, trực quan hóa và mô tả mối liên hệ giữa các yếu tố với trầm cảm.

---

## 🔍 Thông tin tập dữ liệu

Tập dữ liệu gồm 27,901 mẫu và 18 cột, bao gồm:

- `Gender`, `Age`, `City`, `Profession`
- `Academic Pressure`, `Work Pressure`, `CGPA`
- `Study Satisfaction`, `Job Satisfaction`
- `Sleep Duration`, `Dietary Habits`, `Degree`
- `Suicidal Thoughts`, `Work/Study Hours`, `Financial Stress`
- `Family History of Mental Illness`
- **`Depression`**: (0 = không trầm cảm, 1 = trầm cảm)

---

## 🎯 Mục tiêu dự án

- Phân tích thống kê mô tả và mối tương quan giữa các biến.
- Tìm hiểu ảnh hưởng của các yếu tố như áp lực học tập, thời lượng ngủ, tài chính... đến trầm cảm.
- Hỗ trợ định hướng cho các biện pháp can thiệp về mặt tâm lý học đường.

---

## 📊 Thư viện sử dụng

- `pandas`, `matplotlib`, `seaborn`: phân tích và trực quan hóa dữ liệu
- `numpy`, `scipy`: thống kê mô tả và kiểm định

---

## 🚀 Cách sử dụng

1. **Clone repository:**
   ```bash
   git clone https://github.com/your-username/student-depression-analysis.git
   cd student-depression-analysis
