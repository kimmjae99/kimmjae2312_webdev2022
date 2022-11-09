# 11/04 **커밋 내용**

---

## 11/09 수**요일**

39번째 커밋

	If (Input.GetKeyDown(KeyCode.A)) {
			float rnd = Random.Range(-0.2f, 0.2f);
			this.transform.position += new Vector(rnd, rnd, rnd);
	}
	//물체의 각도 변경
	If (Input.GetKeyDown(KeyCode.B)) {
			float rnd = Random.Range(0.0f, 360.0f);
			this.transform.rotation = Quaternion.Euler(rnd, 0.0f, 0.0f);
	}
	//물체의 확대/축소 비율 변경
	If (Input.GetKeyDown(KeyCode.C)) {
			float rnd = Random.Range(0.5f, 1.5f);
			this.transform.localScale = new Vector(rnd, rnd, rnd);
	}