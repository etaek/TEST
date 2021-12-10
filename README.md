JSONArray jsonArray=new JSONArray();
for(Map<String,Object> hm : list) {  // list는 LIST<<>>형태 변수명 쓰면됨
    JSONObject json = new JSONObject(hm);
		jsonArray.add(json);
}

