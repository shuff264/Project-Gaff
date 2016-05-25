using UnityEngine;
using UnityEngine.EventSystems;
using System.Collections;

public class Dragable : MonoBehaviour, IBeginDragHandler, IDragHandler, IEndDragHandler {

	Vector2 offset;

	public void OnBeginDrag(PointerEventData ped){
		offset = new Vector2(this.transform.position.x, this.transform.position.y)  - ped.position;

	}

	public void OnDrag(PointerEventData ped){
		this.transform.position = ped.position + offset;

	}

	public void OnEndDrag(PointerEventData ped){


	}
}
