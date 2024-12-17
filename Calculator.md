namespace WinFormsApp1_huego
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void Result1_Click(object sender, EventArgs e)
        {
            //ข้อความตัวอักษร
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert strimg to number (intrger)
            // double / float = ใส่ค่าเลขจำนวนเต็มเป้นทศนิยมได้
            // int / integer = ใส่ค่าตัวเลขจำนวนเต็ม
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2); // function + - * /
            // ที่มีตัวแปร Result
            // มีคุรวสมบัติชื่อ text
            int iResult = iNum1 + iNum2;
            //
            result.Text = iResult.ToString(); //.ToString = แปรค่าเป้น str
        }

        private void button5_Click(object sender, EventArgs e)
        {
            //ข้อความตัวอักษร
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert strimg to number (intrger)
            // double / float = ใส่ค่าเลขจำนวนเต็มเป้นทศนิยมได้
            // int / integer = ใส่ค่าตัวเลขจำนวนเต็ม
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2); // function + - * /
            // ที่มีตัวแปร Result
            // มีคุรวสมบัติชื่อ text
            int iResult = iNum1 - iNum2;
            //
            result.Text = iResult.ToString(); //.ToString = แปรค่าเป้น str
        }

        private void button4_Click(object sender, EventArgs e)
        {
            //ข้อความตัวอักษร
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert strimg to number (intrger)
            // double / float = ใส่ค่าเลขจำนวนเต็มเป้นทศนิยมได้
            // int / integer = ใส่ค่าตัวเลขจำนวนเต็ม
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2); // function + - * /
            // ที่มีตัวแปร Result
            // มีคุรวสมบัติชื่อ text
            int iResult = iNum1 * iNum2;
            //
            result.Text = iResult.ToString(); //.ToString = แปรค่าเป้น str
        }

        private void button3_Click(object sender, EventArgs e)
        {
            //ข้อความตัวอักษร
            string inputNum1 = Num1.Text;
            string inputNum2 = Num2.Text;
            // convert strimg to number (intrger)
            // double / float = ใส่ค่าเลขจำนวนเต็มเป้นทศนิยมได้
            // int / integer = ใส่ค่าตัวเลขจำนวนเต็ม
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2); // function + - * /
            // ที่มีตัวแปร Result
            // มีคุรวสมบัติชื่อ text
            int iResult = iNum1 / iNum2;
            //
            result.Text = iResult.ToString(); //.ToString = แปรค่าเป้น str
        }

        private void button2_Click(object sender, EventArgs e)
        {
            //ฟังก์ชั่นการ clear ช่องให้ว่าง
            Num1.Text = "";
            Num2.Text = "";
            result.Text = "";
        }
    }
}
