# Chương trình chúc mừng ngày 20/10

def chuc_mung_ngay_phu_nu():
    print("=============================================")
    print("Chúc mừng ngày 20/10 - Ngày Phụ nữ Việt Nam!")
    print("=============================================")
    print("Chúc các chị em luôn vui vẻ, hạnh phúc và thành công!")
    print("=============================================")

def main():
    print("Nhập ngày tháng năm hiện tại (dd/mm/yyyy): ")
    ngay, thang, nam = map(int, input().split('/'))
    
    if thang == 10 and ngay == 20:
        chuc_mung_ngay_phu_nu()
    else:
        print("Ngày hiện tại không phải là ngày 20/10.")

if __name__ == "__main__":
    main()
